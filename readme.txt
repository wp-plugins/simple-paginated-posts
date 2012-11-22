=== Simple Paginated Posts ===
Contributors: tlamedia
Donate link: http://www.tlamedia.dk/
Tags: pagination, post pagination, page pagination, navigation
Requires at least: 3.2
Tested up to: 3.5
License: GPLv2 or later
Stable tag: trunk

Generate table of contents for paginated posts 

== Description ==

The Simple Paginated Posts plugin uses the native WordPress Page-Link tag `<!--nextpage-->` in combination with a shortcode tag [spp title="My title"] to generate a Table Of Contents for paginated posts.

= Implementation =
You simply define a title for the Table Of Contents (TOC) by placing a SPP shortcode tag right after the `<!--nextpage-->` tag.

Example:
<!--nextpage-->
[spp title="My title"]

The plugin can be configured to automatically add the TOC and page links to your site. You can also choose manual implementation and add the template functions to your theme.

If you choose to implement Simple Paginated Posts (SPP) manually you need to insert the SPP template functions in your theme

    spp_continued() - Displays "Continued from PREVIOUS TITLE"
    spp_toc() - Displays the Table Of Contents
    spp_link_pages() - Displays: Previous 1 2 3 4 Next

Please refer to the plugin homepage for full documentation of the template functions.

== Installation ==

1. Upload the `simple-paginated-posts` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Changelog ==

= 0.1 =

* Initial beta release.

== Upgrade Notice ==

= 0.1 =
This is the first beta release so please don't use the plugin in production.
