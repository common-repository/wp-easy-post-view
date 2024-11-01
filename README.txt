=== WP easy post view ===
Contributors: Shadabjaffri110
Donate link: http://themeflock.com/donate
Tags: postviews, post, views, count
Requires at least: 3.0.1
Tested up to: 4.0
Stable tag: 2.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Display total views of each post in no time.

== Description ==

This is very lightweight plugin which shows total post or page views count on each post/page just we have to do is install the plugin and add the code
given in installation notes to single.php or any other
page where we wish to display counts

For more free plugins and themes visit <a href="http://themeflock.com/">ThemeFlock</a>

== Installation ==

You can download and install WP-easy-post-view using the WordPress plugin installer. If you wish to do it manully just download WP-easy-post-view and upload it to wordpress plugin directory i.e "/wp-content/plugins/"
and activate WP-easy-post-view from plugin section.
e.g.

1. Upload `plugin-name.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Place `<?php
setPostViews(get_the_ID());
echo getPostViews(get_the_ID());
?>` in your templates

== Frequently Asked Questions ==

= How do is show count on each post? =

Just add the code given in installation note to single.php of your theme 

= Can i show counts on pages as well? =

Yes, you just have to add same code in page.php of you theme.

== Screenshots ==

1. screenshot1.PNG

== Changelog ==

no changes yet.

== Upgrade Notice ==

no upgrade notices.