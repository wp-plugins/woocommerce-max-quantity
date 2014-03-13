﻿=== WooCommerce Max Quantity ===
Contributors: isabel104
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=me%40isabelcastillo%2ecom
Tags: woocommerce, max quantity, cart maximum, max purchase, cart max, cart limit
Requires at least: 3.7
Tested up to: 3.8.1
Stable Tag: 1.1.8

License: GNU Version 2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Set a universal limit for the max quantity, per product, that can be added to cart. Does not require customers to log in.

== Description ==
WooCommerce Max Quantity is an extension for [WooCommerce](http://wordpress.org/plugins/woocommerce/) that lets you set a max limit for the number of items that can be added to the cart. It's a universal limit, meaning this limit affects all products in your WooCommerce store. 

**NOTE:** This plugin only works with "Simple" products. **It does NOT work with products that have "variations".**

The limit is per product, not per the entire cart. 

This works for guest buyers, as well as logged-in buyers.

To set the number, go to your WordPress dashboard. Go to WooCommerce -> Settings -> Products tab. Click "Inventory". Scroll down to "Maximum Quantity Limit Per Product". Set your desired limit there.


**Other Notes**

For more info, see the [FAQ](http://wordpress.org/plugins/woocommerce-max-quantity/faq/).

For support, please use the [Support forum](http://wordpress.org/support/plugin/woocommerce-max-quantity).

Contribute or fork it [on Github](https://github.com/isabelc/Woocommerce-Max-Quantity).

== Installation ==

1. Download the plugin file (`.zip`).
2. In your WordPress dashboard, go to "Plugins -> Add New", and click "Upload".
3. Upload the plugin file and activate it.
4. Go to WooCommerce -> Settings -> Inventory tab, and scroll down to the one setting: "Maximum Quantity Limit Per Product". Set your desired limit number there.

== Frequently Asked Questions ==

= Why don't you add support for products with variations? =

I don't have the time at the moment to add it with enough options for backwards compatibility for those who do not want this feature. (There are those who do not prefer this feature. For example, if you want to limit sales to 3 T-shirts, regardless of T-shirt size.) I may add this feature in the future, when I get time. You are welcome to hack away [on Github](https://github.com/isabelc/Woocommerce-Max-Quantity).


== Screenshots ==

1. The setting at WooCommerce -> Settings -> Inventory tab

== Changelog ==

= 1.1.8 =
* Fix: now checks for manually-typed quantity because maximum limit was able to be overridden by typing in a number.
* Fix: a problem in which limit was ignored if product was previously added to cart, then added another item to cart, then re-added this item to cart.
* Maintenance: Updated description to reflect that this plugin does not yet support products with variations.

= 1.1.6 =
* Fix: maximum limit was able to be overridden by adding a new instance of the item to cart.
* Fix: maximum limit was able to be overridden by updating quantity on cart page.

= 1.1.5 =
* Tested for WP 3.8 compatibility.

= 1.1.4 =
* Tested for WP 3.7.1 compatibility.

= 1.1.3 =
* bug fix related to syncing with Git.

= 1.1.2 =
* bug fix related to syncing with Git.

= 1.1.1 =
* bugfix related to syncing with Git.

= 1.1 =
* Tested for WP 3.6.1 compatibility

= 1.0 =
* Initial release.

== Upgrade Notice ==
= 1.1.8 =
Fix: they can no longer override limit by manually typing quantity. Other bug also fixed.