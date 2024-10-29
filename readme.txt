=== AR Subpages Widget ===
Contributors: bfouzder
Donate link: https://www.thearsoft.com/contributions/wpplugins/
Tags: ar_subpages, widget, subpages, menu, thearsoft
Requires at least: 3.2
Tested up to: 5.6
Stable tag: 2.0
Requires PHP: 5.6.0
License: GPLv3 or later
License URI: https://www.gnu.org/licenses/gpl-3.0.html

Lists subpages of the current parent page

== Description ==

This widget will dynamically list all the subpages. When you are on a page, it will find the parent page and list all the child pages.

It can also include the current page's subpages in the listing.

Feature List- 

* Add filter for changing section parents
* Allow $post to be filtered
* Add unique class to menu items, menu-item-{id}
* Add hook for adding links to end of subpages listing
* Update widget formatting in the backend
* Subpage titles are filterable
* Support for all hierarchical post types
* Only output HTML for classes if there are classes
* Only output subpages ul if there are subpages
* Allow second level subpages to be nested in li
* Add class for the first menu item
* Add filter for widget classes
* Add filter for widget title
* Sort by menu order
* Add a depth parameter to the args filter
* Allow deeper menu (current page's subpages)


You can customize the listing with the following filters:
ar_subpages_widget_args - modifies the arguments passed to wp_list_pages
ar_subpages_widget_display_override - determine when the widget is displayed
ar_subpages_widget_override_post - change the current post
ar_subpages_widget_parents - customize the hierarchy used in querying subpages
ar_subpages_widget_title - customize the widget title
ar_subpages_page_title - customize the page title
ar_subpages_widget_class - customize the classes applied to pages

Contributors:
- [bfouzder](https://profiles.wordpress.org/bfouzder)
- [farjanaroshni](https://profiles.wordpress.org/farjanaroshni)

== Installation ==

1. Upload the plugin zip file to the `/wp-content/plugins/` directory, or install `AR Subpages Widget` through the WordPress plugins screen directly.
2. Activate the `AR Subpages Widget` through the 'Plugins' screen in WordPress
3. Navigate to widget menu from appearance menu add `AR Subpages Widget to your sidebar` and fill-up the form. (see screenshots 1).  


== Screenshots ==
1. Adminpanel Widget form.
2. Widget display on the website.


== Changelog ==

= 2.0 =
* Initial release
