---
layout: feature
section: features

title: Template and Theme Editor
meta_description: MyBB's built-in template and theme editor gives you complete control over your forum's design.

redirect_from:
- /features/05-template-and-theme-editor/
---
## Customization has never been this easy

MyBB includes a revolutionary theme system and an advanced template editor to make customizing your forum easy. Included is syntax highlighting, multiple stylesheet support, both a simple and advanced stylesheet editor, and improved template searching.

## Multiple stylesheets

With MyBB, you can create additional stylesheets that can be used either globally or on individual pages (and individual actions within those pages). This is in addition to the global stylesheet, and a set of pre-included stylesheets that contain styles specific to pages such as the User CP, Mod CP, and thread pages.

<p class="tourScreenshot"><a href="{{ site.url }}/assets/images/tour/template-themes/stylesheets.png" class="fancybox" title="Customizing your forum has been made easy, even for those with no previous design experience."><img alt="Edit stylesheet properties" src="{{ site.url }}/assets/images/tour/template-themes/stylesheets.png" width="500" height="350" /></a></p>

## Attachable base colors

New in MyBB 1.8, attachable base colors allow you to create colors to which you can attach stylesheets (just like you can attach stylesheets to pages). You can also set a display order for all your stylesheets so that they can override styles. Together, the changes mean you can add a theme with as many custom colors as you want. Using the parent/child theme structure that already exists in 1.x you can restrict or allow certain usergroups to use these colors and, as they inherit the main stylesheets, they’re very easy to manage. So, there is no longer the need to install a dozen different themes just for a different color header.

## Simple and advanced theme editors

MyBB lets you easily edit every selector in a stylesheet, not just a predefined set. Rather than displaying these all on a single page, you only edit one selector at a time. This remains quick and easy to use because MyBB uses AJAX to load and save each selector. By doing this, the only content loaded is the content you need - you don't have to reload a lengthy page of options every time you make a minor change to your stylesheets. Finding selectors is easy, too - everything is sorted in alphabetical order.

Additionally, MyBB offers an "Advanced Mode", which allows users who are more familiar with CSS to edit the stylesheet directly. You also can use the Advanced Mode to add new selectors, which you will then be able to edit using the simple editor.</p>

<p class="tourScreenshot"><a href="{{ site.url }}/assets/images/tour/template-themes/theme-editor.png" class="fancybox" title="The simple theme editor makes both designing themes and learning CSS an enjoyable experience."><img alt="Stylesheet editor" src="{{ site.url }}/assets/images/tour/template-themes/theme-editor.png" width="600" height="330" /></a></p>
