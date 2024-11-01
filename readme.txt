=== UM Bootstrap Carousels ===
Contributors: angstypoo
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=bloyeh%40gmail.com&item_name=Open+Source+Plugin+development&currency_code=USD&source=url
Tags: carousels, bootstrap, bootstrap 4, carousel, image carousel, image slider, slider, images
Requires at least: 4.8
Tested up to: 5.2.2
Stable tag: 1.0.3
Requires PHP: 5.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.txt

This plugin allows you to create and manage bootstrap 4 carousels.

== Description ==

#### Create
Create references to carousels using Wordpress admin panel. Each carousel reference lets you add and manage individual items.

#### Implement with ease
Including the carousel is as easy as adding a shortcode to your page.  Details for the shortcode for each carousel are included in the editor.

If you don't want to manually include bootstrap, each carousel editor allows you the option to include it automatically on any page you add the shortcode with that slider's id.

#### Basic Style
This release includes a basic style for your carousel.  To enable it, select a slider, click Settings, and select the "basic" style from the dropdown.
It eliminates some of the requirements for configuring a usable bootstrap 4 carousel including:
* **Making Containing images responsive** :  No matter the dimensions, the image will fill the carousels space responsively
* **Making Other elements responsive** : As the viewport changes size, the text changes size the indicators shift responsively
* **Basic Design** : Includes Google font Raleway, and a transparent block to help visually offset the text color from images

**The plan is to include more styles in later releases**



== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/um-bootstrap-carousels` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Begin Creating bootstrap 4 carousels by clicking Carousels (wp admin menu) > Add Slider/Carousel
4. Manage Existing Carousels by clicking Carousels (wp admin menu) > Carousels (Dropdown) and select your carousel
5. Change Settings for Carousels by clicking Carousels (wp admin menu) > Carousels (Dropdown) > Settings

== Screenshots ==
1. Add a new carousel reference by clicking "Add Slider/Carousel"
2. View a carousel reference by clicking the "Carousels" dropdown and selecting it
3. Change settings for a carousel in "Settings"
4. Edit individual Items with TinyMCE
5. An implemented carousel on the frontend using the "basic" style

== Changelog ==

= 1.0.2 =
* Fixed a bug related to image thumbnail resizing in admin

= 1.0.3 =
* Modified bootstrap inclusion in admin facing pages to only be specific to this plugin

== Frequently Asked Questions ==

= What is Bootstrap? =

Bootstrap is an awesome front-end library for projects on the web.  Out of the box, you can hack together a pretty cool front end without worrying about backwards compatibility, while saving you a ton of time by facilitating many time consuming aspects of front end design for you.

= What version of bootstrap does this require? =

Bootstrap 4.3

= Should I enable automatic bootstrap inclusion? =

This plugin is for people already planning to use bootstrap 4, so if you already included bootstrap, the answer is no.  If you haven't included it, then yes.  Keep in mind that it only enqueues bootstrap on the pages where you include Carousels.

Screenshots and additional info coming soon!
