=== Sub Categories Widget ===
Contributors: magicoli69, BrokenCrust
Donate link: https://magiiic.org/donate/
Tags: widget, category, sub-category, list
Requires at least: 5.0
Tested up to: 6.8.2
Requires PHP: 7.4
Stable tag: 1.5.3
License: AGPLv3 or later
License URI: https://www.gnu.org/licenses/agpl-3.0.html

This Widget lists the sub-categories for a given category.

== Description ==

*Note: This plugin seems abandoned by it's original author, so I took over to ensure maintenance if needed.*

Sometimes when you divide up your WordPress content into categories it all ends up in sub-categories of one or two main categories that don't have any content themselves.

With the widget you can add a list of sub-categories even if the parent doesn't have posts.

You can display and filter sub-categories in various ways:

* Use the parent category as the widget title
* Show post counts in bracket next to the name
* Hide empty sub-categories
* Add a link to the parent category to the widget title
* Show the full sub-category tree so it include sub-sub categories and so on as well
* Display the list as dropdown rather than as links
* Use the first category of the current post as the parent
* Exclude one or more sub-categories from the list
* List the categories in reverse order


== Usage ==

1. Go to **Appearance > Widgets** or **Appearance > Customize > Widgets** in your WordPress admin.

2. Add the **Sub-categories** widget to any widget area (sidebar, footer, etc.).

3. Configure the widget options:
   - **Parent category**: Choose which category's sub-categories to display
   - **Title options**: Use custom title or parent category name as title
   - **Display options**: Show/hide post counts, empty categories, etc.
   - **Layout**: Display as list or dropdown menu
   - **Advanced**: Exclude specific categories, show full tree, reverse order

4. The widget will automatically display sub-categories of your chosen parent category.


== Changelog ==

= 1.5.3 =
* Updated plugin header with new maintainer information (Magiiic/Oli's fork)
* Updated minimum WordPress and PHP requirements
* Tested up to 6.8.2
* Changed license from GPLv2 to AGPLv3
* Added donate link and proper plugin URI
* Updated contributors list to include new maintainer
* Added maintenance note in description
* Improved code formatting and WordPress coding standards compliance
* Enhanced security with proper WPINC check
* Updated text domain loading path
* Added .distignore file for distribution

= 1.5.2 =
* Changed dropdown url function from get_option to get_home_url for compatibility with WPML

= 1.5.1 =
* Fixed issue with a php7.2 depreciation during plugin activation (bug fix)

= 1.5 =
* Added an option to display the categories in reverse order
* Added the ability to change the selection label text of the dropdown list

= 1.4.1 =
* Fixed missing parent category notice on pages when using irst category of the post option

= 1.4 =
* Added an option to use the first category of the post as the parent
* Improved and updated sanitation and validation

= 1.3.01 =
* Updated the dropdown to be in name order (to match the list)

= 1.3 =
* Added option to show as dropdown list
* Tidy of widget options area

= 1.2 =
* Added ability to exclude categories (with a comma delimited list)
* Added option to show the entire sub-category tree rather than just one level

= 1.1 =
* Highlights the current category if on a category archive page (use .current-cat to style)

= 1.0 =
* First Production Release

= 0.1 =
* Initial Release
