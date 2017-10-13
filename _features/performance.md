---
layout: feature
section: features

title: Performance
meta_description: MyBB has been designed to be efficient for all forums, large or small.

redirect_from:
- /features/14-performance/
---
## So fast, you're still going to be chasing it

MyBB 1.2 was fast and efficient for what it needed to do. We made further improvements with MyBB 1.4 though to make it even faster and handle larger sized forums than what were previously possible.

Working closely some of the largest forums on the web has allowed us to determine the bottlenecks in MyBB 1.2 and completely eradicate them from MyBB 1.4.

While developing MyBB 1.8 we dug deeper to find areas which had fallen behind. With the introduction of new cache handlers, improve debugging information, and the removal of unnecessary queries, we're proud to say MyBB is still one of the fastest yet feature rich forum solutions available today.

## Built-in support for eAccelerator, APC, memcached and X-Cache caching

In a standard installation of MyBB, we already cache the most frequently accessed items (a list of forums, user groups, birthdays, settings, etc) to either the database or the file system. While this is a great speed and optimization improvement, having this information stored in memory on the server is quicker once again.

MyBB also has the ability to store cached information using built-in shared memory caching from PHP modules such as X-Cache and eAccelerator and also has the ability to interface with memcached servers for cache storage.

# Delayed thread view counter updates

MyBB keeps track of whenever a user views a thread to provide the number of views it's received. For larger forums, constantly updating this in the threads table meant tables were locked by the database server and posting time & modification would be affected.

It's now possible to have the number of views a thread receives updated in batches by the automated task scheduling system. The number of views a thread receives can now optionally be updated every X minutes instead of instantly.
