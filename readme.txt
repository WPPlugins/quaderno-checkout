=== Quaderno Checkout ===
Author URI: http://quaderno.io
Contributors: polimorfico
Tags: stripe, paypal, braintree, paymill, stripe checkout, vat, eu vat, vatmoss, vat moss, european vat, eu tax, european tax, billing, invoicing, receipts
Requires at least: 3.7
Tested up to: 4.8
Stable tag: 1.8.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Send beautiful receipts to your customers and comply with international tax rules for digital goods & services, including EU VAT MOSS.

== Description ==

This plugin requires a [Quaderno](https://quaderno.io) account.

Quaderno Checkout is an embeddable payment form for desktop, tablet, and mobile devices. It works within your site—customers can pay instantly, without being redirected away to complete the transaction.

Quaderno Checkout **works with Stripe, PayPal, Braintree, and Paymill**. It calculate VAT rates for EU customers on-the-fly and sends beautiful PDF invoices to your customers automatically.

**Setup in less than 5 minutes**. Easy and quick!

1. Activate the plugin, go to Settings > Quaderno Checkout, then enter your Quaderno keys.
2. Edit the post or page where you want the payment button and checkout form to appear.
3. Add a simple shortcode.

Here are a few shortcode examples (amounts in U.S. cents):

`[quaderno amount="1000" description="Sample Product" redirect_url="thank-you-page.php"]`

`[quaderno amount="1000" description="Sample Product" gateway="paypal" redirect_url="thank-you-page.php"]`

`[quaderno amount="1000" description="Sample Product" panel_label="Now only {{amount}}!" redirect_url="thank-you-page.php"]`

[Shortcode Documentation](https://quaderno.io/docs/plugins/wordpress/)

== Installation ==

Following are the steps to install Quaderno Checkout

1. Unpack the entire contents of this plugin zip file into your wp-content/plugins/ folder locally.
2. Upload to your site.
3. Navigate to wp-admin/plugins.php on your site (your WP Admin plugin page).
4. Activate this plugin.
5. Configure the options from the Quaderno Menu.

OR you can just install it with WordPress by going to Plugins > Add New > and type this plugin's name

That's it! You can now be digital tax compliant.

== Frequently Asked Questions ==

= Do I need to modify any code? =
Nope - we take care of everything you. Just install the plugin, add your API token and you’ll be good to go!

= Does Quaderno work with any themes? =
Yes, Quaderno works with any theme - whether free, commercial or custom. You just need EDD activated for Quaderno to work.

= Does Quaderno Checkout work with cache plugins, like WP Super Cache? =
No. You have to deactivate the cache on all your checkout pages. Otherwise Quaderno won't work properly.

If you have any questions please get in touch with us at hello@quaderno.io.

== Screenshots ==

1. Checkout form
2. Copy your API keys from your Quaderno account
3. Paste it on the plugin settings page
4. Example of a receipt

== Changelog ==

= 1.8 =
* New: WordPress 4.7 compatibility
* New: WordPress 4.8 compatibility

= 1.7 =
* New: Support PayPal subscriptions
* New: Add new atributes for one-off purchases
* Fix: error in Paypal subscriptions
* Fix: problem with payments of Braintree and Paymill

= 1.6 =
* New: Select customer type to show/hidden business data
* New: Add form attribute so that Rocket Loader ignore Checkout script

= 1.5 =
* New: Add custom styles to main button

= 1.4 =
* New: Allow change the button color

= 1.3 =
* New: Allow tax-included payments

= 1.2 =
* New: Set transaction type
* New: Send description to PayPal
* New: Hide VAT number is the customer belongs to certain country
* Fix: error for standard transactions

= 1.1 =
* New: Ask for the customer billing address

= 1.0 =
* First version