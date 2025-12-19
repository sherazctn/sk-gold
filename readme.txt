=== SK Gold ===
Contributors: sherazkhan
Tags: gold price, dynamic pricing, woocommerce gold, jewelry pricing, gold api
Requires at least: 5.8
Tested up to: 6.9
Stable tag: 3.3.6
Requires PHP: 7.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

SK Gold automates jewelry pricing for WooCommerce stores using manual rates or live API feeds.

== Description ==

SK Gold is a robust WooCommerce extension designed for jewelry stores. It automatically calculates product prices based on:
1. Gold Karat (14K, 18K, 21K, 22K, 24K)
2. Weight (in grams)
3. Current Gold Rate (Manual or API-based)
4. Market Gap & Markups

**Key Features:**
* **Live Gold Rates:** Optional integration with GoldPriceZ API (requires API key) to auto-fetch rates hourly.
* **Manual Control:** Override any karat rate manually.
* **Market Gap:** Add a global "Market Gap" (e.g., +2 AED) to the base gram rate.
* **Dynamic Pricing:** Automatically updates Simple and Variable product prices when rates change.
* **Transaction Logs:** Detailed history of every rate update, user action, and API fetch.
* **Shortcodes:** Display live rates anywhere on your site (e.g., `[gold_price_24]`).

**Third-Party Service Disclosure:**
This plugin connects to an external service, **GoldPriceZ**, to fetch live gold rates (AED) if the user enables the API feature.
* **Service URL:** https://goldpricez.com/
* **Data Transmission:** The plugin sends an HTTP GET request containing only the user's API key. No personal user data is shared.
* **User Control:** This service is optional. Users can uncheck "Use API" in settings to manage rates manually.

== Installation ==

1. Upload the plugin folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Go to "Melix Gold" in the admin menu to configure your API key or manual rates.

== Frequently Asked Questions ==

= Do I need an API key? =
No. You can enter gold rates manually. However, if you want automatic hourly updates, you need a GoldPriceZ API key.

= Does this work with Variable Products? =
Yes. You can set the weight and karat for specific variations, and the plugin will calculate the price for each variation independently.

== Screenshots ==

1. General Settings with API status.
2. Gold Rates management with Market Gap support.
3. Detailed Logs showing rate changes.

== Changelog ==

= 3.3.6 =
* Initial release on WordPress.org.
* Added detailed logging and filtering system.
* Improved WooCommerce variation support.