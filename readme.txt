=== Restricted content based on purchase ===
Contributors: maciex777
Tags: restricted content, hidden content, content restriction, access control, private, permission, restrict access
Requires at least: 4.0
Tested up to: 5.8
Stable tag: 1.0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Restricted content for users who have not purchased the indicated product or product variant.

== Description ==

With this plugin, you can mark the content of posts, pages or other products as visible only to users who have purchased the selected product or its variants.

Major features in Restricted content based on purchase include:

* All content can be hidden in a specific post, page or product options or part of it can be hidden with a shortcode.
* You can set a default text to appear in place of restricted content.
* A custom or automatically generated excerpt with a fade out effect may also be shown in place of the restricted content.
* You can set up redirection so that the user who have not purchased the indicated product cannot enter the post and will be redirected to another page.
* WooCommerce is needed for the plugin to work.

The plugin is a simple solution for websites offering paid content such as online magazines, courses, etc., that do not need an extensive system with many features, but instead need the ability to limit the visibility of the content based on the purchase of the product.

**Includes the following translations:**

* Polish (pl_PL)

== Screenshots ==

1. Plugin settings page in the Restricted content menu admin tab.
2. Restricted content options in the post editing screen.

== Installation ==

1. Make sure WooCommerce is installed. 
2. Upload the plugin to your WordPress site and activate it.
3. Go to `Restricted Content` page, where you can change what settings you need.
4. Set restricted content options in the post or page edit screen. 

== Frequently Asked Questions ==

= How to use the shortcode? =

You can limit the visibility of content by using a shortcode - just wrap the content between [rescon id="33"] and [/rescon]. Enter the product id as value of the "id" attribute.

= Where can i get product id? =

Enter the product edit screen and see what number is in the url after ?post=. This is product id. Variants id are shown next to each variant item in the Variants tab.

= Why is the length of the excerpt different than the length specified in the restricted content settings? =

Probably the post/page has its own custom excerpt. The length in the restricted content settings refers to the automatically generated excerpt extracted from the content of the post/page. 

== Changelog ==

= 1.0.1 =
*Release Date - 30 August 2021*

* added background compatibility of the excerpt with the global color background when the fading effect is enable

= 1.0.0 =
*Release Date - 26 August 2021*

* First stable version.
