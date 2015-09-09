=== Latest Posts by Author with content ===
Contributors: opensourcetech
Tags: posts, authors,content
Requires at least: 2.8
Tested up to: 4.2.2
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Displays an unordered list of an author's latest posts with content.

== Description ==

This Plugin is extended version of "Latest Posts by Author" Wordpress plugin. This plugin allows you to display an unordered list of links to a specific author's latest posts (or a list of multiple authors). It can be called either with a shortcode or from within a theme file.

To call it with a shortcode, use `[latestbyauthor author="username" show="3"]` where "username" is the login name of the author (or a comma separated list of multiple authors) and "3" is the number of posts to display. If you don't specify an author or a display number, it will show the latest 5 posts from the author of the current page. If you want it to display the post excerpt as well, you can use the following code: `[latestbyauthor author="username" show="3" excerpt="true"]` This will only show exerpts that you have entered manually.

To call it from within a theme template, you have to wrap it in this PHP function: `<?php echo do_shortcode('[latestbyauthor author="username" show="3"]'); ?>`

<p>For video tutorial : <a href="https://www.youtube.com/watch?v=Lg3nBWofBZY&feature=youtu.be" target="blank" >Click here</a>
</p>
== Installation ==

1. Upload the `latests-posts-by-author` folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Place `<?php echo do_shortcode('[latestbyauthor]'); ?>` in your templates or `[latestbyauthor]` in your posts

==Screenshots==

For Screenshots, please visit:<p>http://www.opensourcetechnologies.com/wordpress-plugins/latest-posts-by-author-with-content.html</p>
