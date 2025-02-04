=== ExchangeWP: Simple WP Ecommerce ===
Contributors: ExchangeWP, ajmorris
Tags: ecommerce
Requires at least: 3.7
Tested up to: 4.8
Stable tag: 1.36.8
License: GPLv2 or later

Easily sell your digital and physical products with ExchangeWP, simple ecommerce for WordPress

== Description ==

= Sell Your Stuff Online in Under 5 Minutes =
ExchangeWP makes it easy to get your store up and running quickly by making the process simple. Just install, activate, choose your payment methods and start adding your products.

= A Simple Interface =
Your products are not blog posts. So we created an experience that makes creating products simpler and more intuitive.

= Simple but Extendable =
An online store can get pretty complicated. And not everyone needs the same things. With ExchangeWP, many features are split into add-ons. You only see what your store needs, making it simple to use and manage.

= Get Paid with PayPal or Stripe =
We designed ExchangeWP's purchase experience with Stripe as the ideal payment gateway. Stripe is awesome. If you've used it, you know.

PayPal Standard (Basic or Secure) is supported out of the box as an ExchangeWP core add-on . But we want you to have the easiest store experience with Exchange, so we're now offering the Stripe add-on for free.

= Customer Management Made Easy  =
We don't create our own database tables for customers. We use the same built-in WordPress user system and add customer data to its own page, making it simple to edit their transactions, view available downloads and make customer notes for your reference.

= More Features =
For more information on ExchangeWP features and available add-ons, visit: http://exchangewp.com

= Add-ons =

Add only the features you need. ExchangeWP Add-ons include support for several payment gateways, coupons, digital downloads, sales reports, multi-item cart, product categories and product tags.

* Accept PayPal Standard or Offline Payments - Process transactions out-of-the-box with PayPal Basic or PayPal Secure or take payments offline to process cash or check payments.
* Stripe - Enable the free Stripe Add-on to process payments with Stripe, our recommended payment gateway.
* Coupons - Generate basic coupons that apply to all products in your store.
* Multi-item Cart - Allow customers to purchase multiple products with one transaction.
* Basic Reporting Dashboard Widget - View basic sales statistics from the WordPress admin dashboard.
* Digital Downloads - Add a product type for distributing digital downloads through ExchangeWP.
* Product Categories and Tags - Organize your store by grouping with category and tag taxonomies.
* Guest Checkout - Enabling this add-on gives customers the ability to checkout as a guest, without registering.
* Billing Address - Collect a billing address at checkout.
* Customer Pricing - Let customers choose their price from a list of price options you create or let them enter their own price.
* Simple Shipping - Adds flat rate and free shipping for your physical products.
* Simple Taxes - This gives the admin ability to apply a default tax rate to all sales.
* Membership - Create as many memberships as you want with specific rules for what content your members can access. You can also use the Memberships add-on to delay (or drip) content access like in a daily, weekly or monthly course.

= Advanced Product Options =

ExchangeWP allows you to create products quickly and easily. But sometimes you need more than just the basics, so Advanced Product Options help by offering additional ways to manage products.

* Download Expirations - Apply settings for download links to expire or to limit access to download links/file downloads.
* Product Availability - Apply product availability start and end dates.
* Product Inventory - Set and track product inventories.
* Hidden Source Files for Digital Product Downloads - Use source file URLs from the WordPress media library or from Dropbox, Amazon, etc. and exchange automatically hides this source URL for digital product downloads.
* LoopBuddy compatibly - Use LoopBuddy queries and layouts for individual product.
* Builder compatibility - Apply iThemes Builder layouts for individual products.

= Payment and Customer Management =

View transaction details and manage customers from within Exchange.

* Payment/Transaction Details - See order number, payment total, status, customer, payment method and date of payment for individual transactions.
* Customer Registration - Use Exchange Registration or WordPress Registration settings.
* Customer Data - Manage customers by viewing products purchased, transactions or add notes to customer info.
* Issue Refunds or Resend Confirmation Emails - Easily issue refunds or resend confirmation emails for individual customers.

= Customizable Emails =

Use the WordPress WSIWYG editor to make custom email templates for Admin Sales Notification emails and Customer Receipt Emails. HTML is accepted.

* Admin Sales Notification Emails - Customize the email sent to admins for sales notifications.
* Customer Receipt Emails - Customize the receipt emails customers receive after making a purchase.
* Email Shortcode functions - Use built-in shortcode functions in emails for customer name, full name, username, download list, order table, purchase date, total, payment id, receipt id, payment method, site name and receipt links.

== Installation ==

Upload the Exchange plugin to your blog, activate it and enable the Digital Downloads add-on and a transaction method add-on. For more information, visit:
http://support.exchangewp.com/article/20-exchangewp-installation

== Developer Emeriti ==
ithemes, blepoxp, layotte, aaroncampbell, mattdanner

== Changelog ==
= 1.36.7 =
* Rebrand: iThemes Exchange to ExchangeWP
* Rebrand: Links point to ExchangeWP
* Rebrand: Removing upsell of iThemes Products and ExchangeWP products

= 1.36.5 =
* Fix: Ensure invalid transaction activity items are not returned.
* Fix: PHP 7.1 compatibility.
* Fix: Follow redirects when serving downloads.

= 1.36.4 =
* Fix: Account for new return types in iThemes Security reCaptcha Module

= 1.36.3 =
* Tweak: Account for plugins or themes flushing rewrite rules in a non-admmin context.

= 1.36.1 =
* Fix: Variable name for superwidget error output

= 1.36.0 =
* Update: Updating lib/classes to v2.4.8

= 1.35.11 =
* Security: Fix serious XSS vulnerability
* Fix: Issue with fallback SW filter being triggered in incorrect places
* Fix: Compatibility with BuddyPress
* Fix: Missing break statements in Theme API.

= 1.35.10.2 =
* Fix: Issue with the Super Widget not rendering. Improve detection of "loop_start"

= 1.35.10.1 =
* Fix: Issue with the Super Widget not rendering when 'the_content' is applied before the main content area.

= 1.35.10 =
* Fix: Issue with the Super Widget not rendering correctly
* Tweak: Add support for sale price to make a product free

= 1.35.9 =
* Fix: PayPal Standard Secure intermittent 502 errors
* Fix: Don't render the Super Widget in the sidebar if it is already displayed as a shortcode.
* Tweak: Don't autoload transient transactions
* Tweak: Update lib/classes

= 1.35.8 =
* Add: it_exchange_convert_country_code() API function
* Fix: Don't overwrite existing columns on the products list table
* Fix: ITSEC Recaptcha Integration
* Fix: Ensure tooltip dialog clears other DOM elements

= 1.35.7 =
* Add: Filter to the max quantity check for Variants
* Add: BN Code to PayPal Gateways
* Tweak: Only require shipping address when necessary
* Fix: Errors with deleted users and transaction activity
* Fix: Errors with Guest Checkout and transaction activity

= 1.35.6 =
* Fix: Metaboxes on the menus page were being incorrectly hidden.
* Fix: t_paamayim_nekudotayim on PHP 5.2

= 1.35.5 =

* Tweak: Extract session interface, IT_Exchange_SessionInterface, for managing sessions.
* Tweak: Better activity messages for renewal payments.
* Fix: Zero Sum Checkout subscriptions losing access
* Fix: Offline Payments subscriptions losing access
* Fix: Stripsllashes after jquery date format is replaced
* Fix: Move subscription status activity reporting to Recurring Payments
* Fix: Remove cancel URLs for zero sum checkout and offline payments
* Fix: Only break-words on code tags in the activity stream
* Fix: Logic for toggling offline payment subscriptions back to active after a payment has been received
* Fix: Warning with get_class()

= 1.35.4 =
* Fix: Cart ID should always be present
* Fix: Coupons not being counted more than once
* Tweak: Mark Zero Sum Checkout and Offline Payments subscriptions as Active when paid

= 1.35.3 =
* Add activity item whenever a method ID changes
* Display method ID in transaction details

= 1.35.2 =
* Fix: Ensure line breaks are preserved
* Fix: Make it possible for add-ons to register custom upgrades
* Fix: Possible null error with transaction activity
* Fix: Runaway upgrades
* Tweak: Better display for upgrade exceptions

= 1.35.1 =
* Tweak: Use shorter date format in the admin
* Fix: Error for PHP 5.3
* Fix: Use HTTP/1.1 for PayPal requests

= 1.35.0 =
* Add: IT_Exchange_Product_Factory to allow for custom classes per-product type
* Add: Support for per-cart and per-product coupon discount types
* Fix: Allow for wp-author product feature
* Fix: Ensure upgrade routine progress bar is set to 100% when upgrade completes
* Fix: Don't get stuck in the cart state if multi-item cart is disabled in the SW shortcode
* Fix: Don't duplicate the_content functions on the extended-description

= 1.34.3 =
* Fix: Ensure purchase quantity is always at least one

= 1.34.2 =
* Fix: Fatal error on coupons list table for coupons spanning more than one year.

= 1.34.1 =
* Add: Support for non auto-enabling add-ons
* Fix: Bug preventing PayPal Sandbox from working

= 1.34.0 =
* Add: Transaction Activity Timeline
* Add: Customer Order Notes core-addon
* Add: Support for internal order notes
* Add: iThemes Security Recaptcha Integration
* Tweak: Improve Child Transaction UI
* Tweak: Add succeeded as a valid PayPal status for child payments
* Fix: Changing label in Simple Taxes does not change email receipt
* Fix: Remove upgrades available nag, when no upgrades available.
* Fix: Not all download files are carried over when product duplicated
* Fix: Mitigate possible corrupt session data
* Fix: Remove metabox drag styles on mobile

= 1.33.1 =
* Fix: Issue with Authorize.net

= 1.33 =
* Add: Support for per-customer coupons, per-product category coupons, and excluding products.
* Add: Track number of coupon uses.
* Add: Reduce coupon usage count on cancellation
* Add: Upgrade routine for coupons.
* Add: Support for Exchange Ghost pages in the Customizer
* Add: Autocomplete support for purchase dialogs
* Tweak: Mobile improvements for purchase dialogs
* Tweak: Allow searching by coupon code
* Tweak: Improve coupon error messages
* Tweak: Display sale price in products list table
* Tweak: Style tweaks
* Fix: Prevent PayPal from adding multiple transactions during guest checkout
* Fix: Allow a simple tax rate of 0%
* Fix: Allow for non-physical products to be excluded from shipping calculations

= 1.32.1 =
* Tweak: PayPal Locking Mechanism Updates
* Fix: Create transactions for web_accept in PayPal during IPN, if necessary
* Fix: Adding user nickname/nicename to Profile loop template, required in WP4.4 now
* Fix: DBSessions, esnure sessiosn IDs are valid MD5 hash
* Minor: CSS updates

= 1.32.0 =
* Major: Template parts have been updated: super-widget-product, super-widget-cart
* Add: The SuperWidget can now be embedded using the [it_exchange_sw] shortcode
* Add: Products can now have a sale price
* Add: New core-addon Sale Schedule to restrict sale availability
* Tweak: Make deactivating a plugin from the core-addons page more straightforward
* Tweak: Replace usages of get_class with instanceof to allow for more robust add-ons
* Tweak: Remove the downloads hash from the downloads page by default
* Fix: Adding categories from the edit product page
* Fix: Update the transaction status property when the status changes
* Fix: Ensure comment and ping status is closed. WordPress 4.4 compatibility

= 1.31.0 =
* PayPal Quantum-Locking
* Transient Transaction Code Cleanup
* General Code Cleanup

= 1.30.0 =
* Fixing typo in Transient Transaction Cleanup
* Updating lib/classes

= 1.29.0 =
* Fix for PayPal IPN race conditions
* Fix bug causing shipping method overrise save issues when PHP Suhosin is compiled
* Changing registration and login page default redirects to account page rather than profile page

= 1.28.0 =
* PHP7 Updates from Timothy Jacobs (Iron Bound Design)
* Fix for Inventory Bug from Timothy Jacobe (Iron Bound Design)
* Bug fix for race condition when PayPal IPN comes before PDT

= 1.27.0 =
* Changing init priority for db sessions, to happen before widget_init

= 1.26.0 =
* Fix for registartion and checkout redirect bug

= 1.25.0 =
* Better Output Buffer Cleaning for Plugins/Themes that have created multiple levels of Output Buffer that we need to escape
* Change how DB sessions initialize

= 1.24.1 =
* Adding another check for product_id in cart products

= 1.24.0 =
* Adding extra checks for product_id and count in product array... in case the cart is corrupted and causes isues

= 1.23.0 =
* End and clean the buffer before attempting to readfile/download...
* Remove wp_new_user_notification calls, because this is handled by edit_user now

= 1.22.0 =
* Let it_exchange_shipping_address_purchase_requirement_enabled filter enable save to shipping address on billing form
* Lazy loading the ITE session - Timothy B. Jacobs
* Admin AJAX session fix - Nikola Nikolov

= 1.21.0 =
* Favor home_url over site_url

= 1.20.0 =
* Don't escape email notification URLs with &amp; because &#308; breaks in the browser
* Fix for adding new downloadable files to previous purchases
* Change how we determine if an addon is core

= 1.19.0 =
* Adding email address to Guest Customer label in transaction table
* Changing itExchangeSWAjaxURL to use get_site_url() to help with potential SSL conflicts

= 1.18.0 =
* Better serve filenames when downloading w/ query args
* Adding 301 and 302 as valid response codes for download headers...
* Updating zoom JS and related functionality
* Removing action hook to add shipping to order table from the shipping addon and adding it in the shipping class
* Format the pricing for shipping total in email template
* Adding hooks to order_table email notification template, added action for coupons, simple shipping, and simple taxes to modify email notification order_table template
* Adding Instructions after purchase message to email notifications when Offline Payments are processed
* Added some styling and changed the text a bit to make it clearer what 'No downloads found' means in the context of the downloads page showing 'downlaods' but downlaod
* Fixed Guest Checkout Coupon Limitation bug
* Removing 'total' from Cart page... reserved for Checkout page only Adding taxes column to confirmation page
* Fix for 'Most Used' categories tab not saving, update feature image JS to use .on() instead of .live()

= 1.17.0 =
* Fixing typos
* Don't lose State focus when Country changes in billing/shipping requirement

= 1.16.0 =
* Updated JS Error to say 'Your photo must have a thumbnail created for it that is larger than 150x150px'
* Fixing typo with 'site-name' text
* Updated lib/classes to 2.4.4

= 1.15.1 =
* Fix bug caused by disabled transaction methods on the quick setup wizard

= 1.15.0 =
* Updated lib/classes to 2.4.3 - Fixed a potential Remote Code Execution (RCE) security hole caused by unsanitized inputs for resizing certain kinds of images and generating zip files. Exploiting this flaw would require third-party code or a privileged WordPress user. Thanks to Ryan Satterfield (http://planetzuda.com) for helping to identify this issue.
* Remove quanity input box if multi-item product is not allowed
* Adding secure/httponly flags to setcookie, taken from original DB Sessions on github
* Adding deactivation warning to paypal addons
* Fix illegal offset error in cart API when admin deletes product that a customer has in the cart

= 1.14. =
* Adding 'email' option to it_exchange_email email notification shortcode

= 1.13.0 =
* Add JS hook to SW after state is updated
* Fixes for Recurring Payments bugs
* Change how I handle my globals... also remove my wp_mail debugs
* Fixed bug causing broken 'View store' link in saved product notification
* Fix JS on Shipping Settings Page
* Modify function converting format of default price coming out of DB
* Fix Flat Rate Shipping for international setups: Backwards Compat to ensure data coming out of DB is always
* Add key'd filter to it_exchange_get_option
* Fixed but that prevented it_exchange_load_addon from ever working

= 1.12.0 =
* Multiple updates involving add_query_arg and remove_query_arg to esc_url()
* Introduce it_exchange_get_admin_menu_capability( $context, $capability )
* Adding filter to shipping address and method requirement, for that rare case when the shipping requirement should be enabled, but isn't

= 1.11.18 =
* Pass shipping to PayPal when available

= 1.11.17 =
* Added filter to shipping address and method requirement
* Added cart object verification to PayPal processing

= 1.11.16 =
* Fix for DB Session bloat bug

= 1.11.15 =
* Deprecate the admin_menu_capability property in IT_Exchange_Admin and replace with a method so that themes can filter it.
* If no username or password is provided on submit from exchange Login page, don't redirect to wp-login.php
* Fix bug in purchase-requirement template part's filter name created by first param. Maintain back_compat.
* Adding IPN Verification to PayPal non-Secure option

= 1.11.14 =
* Strip any non-separator/non-digit character out of price before converting to database number
* Fix for converting to DB number for numbers with unexpected number of decimals places
* If unauthenticated site visitor goes directly to account, profile, or purchases, redirect them to login instead of registration
* Fix bug not displaying quanity option in superwidget if coupons isn't activated
* Fix bug causing all categories in product dropdown widget to have 'selected' attribute
* Update custom dropdown_category function to reflect WP Core changeset https://core.trac.wordpress.org/changeset/31024.
* Sort addons by display name rather than addon-slug
* Preserve logged in Guest when updating shipping method on Cart page
* Add ability for store owners to change Guest Checkout heading text and button labels

= 1.11.13 =
* Updating Duplicate Products for new Invoices update
* Removing unnecessary esc_attr() calls from text that would have valid HTML
* Disable Offline Payment's Purchase button when clicked
* Adding a filter to the Products Post Type hierarchical setting
* Modified it_exchange_is_page() to use 'name' query var instead of product slug

= 1.11.12 =
* Auto-Height for admin advanced area text fields
* Spell reset with two e's
* Allow 3rd parties to tweak the state of the SW
* Change unlimited inventory message
* Don't delete transactions when customer's WP user is deleted

= 1.11.11 =
* Fix bug causing it_exchange_is_page(  ) to always return true when called from SW and  != 'product'
* Fix bug preventing query args from loading correct SW state. Also, prevent cart state on product page if no items are in cart
* Enable translation mo file to be overridden in wp-content/languages/plugins/it-exchange

= 1.11.10.1 =
* Fixed function reference in PayPal Standard (basic).

= 1.11.10 =
* Fixed function reference in PayPal Standard (basic).
* Verify quantity functionality in one more place to prevent bug of adding multiples of an item when multiples shouldn't be allowed.
* Restricted Super-Widget JS calls to only the Super-Widget HTML.

= 1.11.9 =
* Sort the advanced metaboxes alphabeticallyi. props Timothy Jacobs <http://ironbounddesigns.com/>
* Adding post vars to actions in print_transaction_details_metabox()

= 1.11.8 =
* Fixed feature to always populate current product in GLOBAL. props Timothy Jacobs <http://ironbounddesigns.com/>
* If cart is not available, use site URL for cancel_return in PayPal add-ons
* Upating PayPal add-ons to work with latest Recurring Payments options

= 1.11.7 =
* Don't pre-check box to mailchimp subscription in Exchange Startup Wizard
* Fix for DB Session Cleanup
* Add a filter to the individual product description when generated for the cart description
* Add product-[ID] and product-[product-type] class names to store product li elementes by default. Make filterable as well.

= 1.11.6 =
* Fix bug preventing users with '&' in their username from logging in via SW. props Timothy Jacobs <http://ironbounddesigns.com/>
* Remember the shipping address when errors are present on SW form. props Timothy Jacobs <http://ironbounddesigns.com/>
* Remember the billing address when errors are present on SW form. props Timothy Jacobs <http://ironbounddesigns.com/>
* Remember the registration fields when errors are present on SW form. props Timothy Jacobs <http://ironbounddesigns.com/>
* Fixed bug that tries to display disabled Exchange profile pages on the user's profile page. props Timothy Jacobs <http://ironbounddesigns.com/>
* Fix bug causing menu item titles to not display when user_is_logged_in and Exchagne login/logout pages are set to 'disabled' in Settings
* Properly escape in values in the event that poorly-formatted option names were previously inserted into the options table
* Fixed improper order of args in call to _x()
* Add new status to param of actions triggered when a transaction status is changed.
* Fixed bug that was preventing default WP welcome email from being sent when new users register
* Extend inline-docs a bit for saving custom billing address fields

= 1.11.5.1 =
* Fix missing font-icons

= 1.11.5 =
* Adding IP address of customer to Transaction meta and on the Transaction page
* Define settings var in IT_Theme_API_Store::products before count since new filter added
* Adding it_exchange_store_get_products_args to count() call in IT_Theme_API_Store::products (to prevent memory leaks when count() doesn't match the next call)
* Adding filter/functionality to disable multiple shipping methods, even when multiple methods are available

= 1.11.4 =
* Fixed instances where webhooks wouldn't work if ['http_scheme'] wasn't set
* Updated es_MX mo file
* Updated the es_MX po file
* Fixed bad language string in template

= 1.11.3 =
* Fixed bad translation string in order details template part
* Added filters for country and state alternatives in text2select API
* Added loading gif during SW AJAX calls to Register / Login
* Fixed bug causing Stripe webhooks not to reach Exchange in some setups
* Fixed notice when no cart object is returned in zero sum checkout

= 1.11.2 =
* Fixing call to weight meta for product

= 1.11.2 =
* Fixed typo in filter in lib/templates/content-store.php
* Fix bug caused when the shipping methods available to an invidial product is less than that available to the whole cart
* Redux it_exchange_get_cart_products_count() to include option 'feature' arg, to only get counts for products with a certain feature
* Updating tooltip for measurement format in shipping
* Check for a processed transaction before rejecting the transaction for having an empty cart -- a partial fix for a bug in PayPal when clicking the 'click here' link after th
* Just some code formatting updates

= 1.11.1 =
* Clear shipping method on cart product update
* Fixed it_exchange_get_cart_weight to account for product count

= 1.11.0 =
* Added filter to transaction object generator to allow cart taxes to be added
* Broke out weight and dimensions shipping features
* Revamp of it_exchange_process_webhooks to be more secure
* Replaced __() with _x() to provide translation context to '&times;' in multiple files
* Fixed bad strings in Currency data-set
* ChangeMod on translation files
* Add Dutch Translations for Exchange
* Add lang directory and es_MX po/mo files
* Add actions for applying/removing basic coupons to/from cart
* Adding new filters and setting new global for add-ons
* Adding some filters for Table Rate Shipping
* Add Mexican states to states.php dataset. Props: Darryl Clark
* Fixed bug causing JS error when Image Gallery Settings turn zoom off

= 1.10.7 =
* Updated select-to-autocomplete JS from 1.0.5 to 1.0.9
* Replaced update_plugins with manage_options to fix missing coupons and taxonomy menu items from WPMS installs.
* Fixed bug breaking the ability to save billing as shipping when using Guest Checkout
* Fixed bug in it_exchange_db_delete_all_sessions with miscalculated substring
* Added title template part for content-product elements

= 1.10.6 =
* Added function that logs guest user out once they hit the confirmation page.
* Add DOING_AJAX checks to is_admin conditional in guest checkout
* Check for non-empty product ID and product arrays before adding/updating session data
* Add basename param to registered addons if it was added as a param in it_exchange_register_addon()
* Added $params var to the filter for add_details in it_exchange_register_addon();
* Change $_REQUEST to $_POST in it_exchange_register_user
* Multiple modifications to Coupons API to make it more extendable. props Timothy Jacobs <http://ironbounddesigns.com/>
* Added multiple js hooks to to superwidget js
* Add nonce to exchange registration template parts and processing function
* Add nonce to edit profile form
* Change customer var from private to protected so that class can be extended
* Change var holding the last version of exchange where template parts were updated to trigger notice in admin.
* Moved css for Add-ons menu styling to global admin stylesheet from sheet for exchange pages only.
* Changed Swiss Frank symbol from 'Fr.' to 'CHF'
* Core changes to support a unified checkout page in the future:
* - Moved conditional logic to determine if purchase requirement template parts are included out of template part files.
* - Added filters to hide the purchase requirements notification
* - Added new function to unregister purchase requirements
* Changed 'Premuim' to 'Premium' and 'physcial' to 'physical' on Help page
* Added shipping-address as a valid super-widget state when simple shipping is enabled
* Added filter to surpress add-to-cart buttons
* Fixed hook typos in SW template parts
* Fixed JS error in lib/assets/js/edit-product.js when itExchange was not defined
* Sort the Default Currency options by alpha
* Make options in Settings dropdown for symbol position use the selected symbol

= 1.10.5 =
* Added support for ContactBuddy

= 1.10.4 =
* Fixed bug causing Template Updates nag to appear on every upgrade
* Updated add/edit product styles for 4.0
* Changed color of addon-link in admin menu
* Added DocBlock modifications from Timothy

= 1.10.3 =
* Fix for memory leak in sessions

= 1.10.2 =
* Fixed non-object PHP warnings
* Changed subtitle in readme to 'iThemes Exchange: Simple WP Ecommerce'
* Adding new filter and global to IT_Exchange_Shipping, using for Table Rate development
* Execute code on next upgrade to clear all bad data from cached user carts
* Fix bug where we are checking for empty on a JSON string rather than on a PHP decoded version

= 1.10.1 =
* Fixed bug where we were casting rather than checking for a conditional.
* Allow product-type add-ons to modify admin menu_title for clarity
* Fixing Guest Checkouts for addons using transient transactions.

= 1.10.0 =
* Added support for IPN only transactions, fixes bug with users paying without PayPal accounts via PayPal and not clicking to return to the site.
* Added for coupons as add-on
* Added billing_address as a shortcode option to emails
* Added shipping_address as a shortcode option to emails
* Added Builder views for Product Categories and Product Tags when add-ons are enabled.
* Added 'View Store' link after 'View Product' link on product creation / update.
* Fixed auto-return bug, caused by work I'm doing to get the IPN to create transactions if they don't exists
* Fixed typo in PayPal standard payment Url
* Removed 'Edit' from bulk actions option list for Payments
* Fixed bug that limited query for downlodable files to retrieving only 5.
* Sort product downloads by ID
* Fixed typo in PayPal standard payment URL
* Changed 'activate_plugins' to 'manage_options' in admin menu permision params so that Exchange menu shows up in WPMS site with plugins management turned off for site admins
* Added cart_id to transaction object cart details
* Added 'it_exchange_before_empty_shopping_cart' action to it_exchange_empty_shopping_cart()
* Added requirement for WP 3.7 in readme.txt
* Added a cart id to cart data that can be used to identify a single shopping event.
* Fixed error causing it_exchange_get_session_data() to return no data instead of all the data
* Added options param to read function in cart API.
* Added ability to request information from cached user cart rather than current session via cart API
* Fixed product not available theme API text
* Added Sync Integration Notice to Admin
* Fixed bug in offline payments cancel URL function
* Wrap get_admin_url in wp_login_url for sync integration

= 1.9.4 =
* Empty arrays passed through json_encode result in a string that causes json_decode to output an array, but an object is expected by get_object_vars, which outputs a warning on some PHP installs. Checking for empty arrays in session for Cart Sync.
* Register chartjs in exchange for other addons... but don't enqueue it.

= 1.9.3 =
* Decode HTML entities when converting prices to database numbers, otherwise the British Pound &#163; adds 163 to the front of a price!
* Add strip_tags to cart description before appending to paypal standard payment URL
* Allow shortcodes in product description with the_content filter
* Run product description through wp_strip_all_tags when max-length is set

= 1.9.2 =
* Fixed error preventing auto-login after user reg from SW
* Fixed PHP Warning caused by attempt to loop through non-array.\n Fixed PHP Warning caused by undefined param
* Add JS hook to super-widget.js when cart is cleared
* Register correct query arg for confirmation hash when used as sub wp page
* Fixed bug that caused all Menu items to display 'Log Out' if pretty permalinks were not enabled
* Modifed rewrite rule for confirmation page to work with child pages.
* Set flag to flush rewrites if Confirmation page is of WP type and that WP page is updated (in the event that post_parent was updated).
* Fixed PHP warning when submiting billing address on checkout screen
* Changed 'Recent Payments' heading to 'Recent Transactions' in dashboard widget.
* Fixed Bug in transaction total for dashboard widget
* Added ability to manually change paypal standard basic payment status
* Added ability to manually change paypal standard secure payment status
* Sync integration, adding the it-exchange-get-overview verb to handle the dashboard widget
* Added ability to limit coupons frequency per customer
* Fixed bug preventing discount when product ID remains set for coupon but checkbox to limit by product was unchecked"
* Fixed notice when ['wp_query']->queried_object is not an object

= 1.9.1 =
* Fixed PHP error in older versions of PHP

= 1.9.0 =
* Added a bunch of filters for EUVAT modifications
* Modified how shipping/billing addresses are handled for 'required' state fields when the country doesn't have any states (known by Exchange)
* Updated description for multi-item cart core add-on
* Styling updates for confirmation page table
* Adding an action after customers cart is cached.
* Add styling support for nested rows in it-exchange-table
* Sync user carts across browsers and devices: - Caches state of cart anytime it has data added, updated, deleted - Logs session ID to list of active carts for user anytime they log-in - Removes session
* Sync user sessions across browsers if logged-in
* i18n strings in purchase-requirements billing and shipping templates
* Modifications to some filters
* Fix bug in tooltip positioning
* Whitespace in readme and history text files
* Update tested up to
* Fix readme
* Add link to changelog in changelog section of the readme
* Adding the Changelog link to the plugin meta links
* Setup menu items filter to compare path of login/logout URLS, not the full URLs, in case of https/http conflict

= 1.8.2 =
* Wrapped most instances of wp_redirect() inside it_exchange_redirect() to standardize filters
* Fixed same border bug in confirmation table
* Fixed bug where border would break in checkout table when amount is more than one line
* Don't clear shipping method when card product (quantity) is updated
* Changed 'Categories' to 'Exchange Categories' and 'Tags' to 'Exchange Tags' when viewing the Nav Menu page in admin.
* Introduce setting to enable Visual Editor on Product Description Field
* Responsive love for customer data -> transactions
* Fixed line-height for it-exchange-remove-item so the x is in the vertical center
* Add product quantity to Payment Details

= 1.8.1 =
* Fixed bug preventing nav menu from showing up on Product Category and Product Tag archive pages
* Added Continue Shopping button to cart with setting to deactivate in Multi-Item Cart settings
* Add pro-pack block back to addons screen, make it collapsible
* Delete duplicate _it_exchange_transaction_id meta_keys from postmeta and usermeta tables. Runs only if previous version is less than 1.8.1.
* Fixed but causing multiple it_exchange_add_transaction_success actions to fire with each transaction.
* Do not redirect to the wizard when Exchange is activated if its a network activate

= 1.8.0 =
* Zeroed out padding by default on super widget notice messages
* Add tooltip script to add-product page.
* Change jQuery 'on' event to work with dynamicly created nodes in tooltip script
* Introduced multiple core changes to support Variants add-on
* Made it possible to enable tabbed interface for image gallery.
* Fixed save/preview/publish buttons breaking at smaller screen widths
* Removed set height on image gallery thumbnails to fix weirdness on smaller screens
* Fixed the annoying 'Are you sure you want to reload' message on Add/Edit product page
* Updated tax id link on general settings page
* Cannot have empty string max attributes, fix for cart product page
* Added a filter to super widget on missing product IDs
* Made tag maps for Theme API objects extendable.
* Added some tracing in HTML comments for template_part loops/elements if WP_DEBUG is defined as true
* Fixed bug with metabox_title in abstract product features class
1.7.27.1 - 2014-04-18 - Glenn Ansley, Lew Ayotte, Ty Carlson, Elise Alley
* Adding missing image not included with last commit

= 1.7.27 =
* Add pro-pack info to setup wizard
* Add 'At a Glance' for products
* Introduced abstract class for product featuress and implemented in inventory

= 1.7.26 =
* Fixed issue with tracking membership cancelationg for PayPal Standard (Secure)
* Verify billing address saved before outputting that it saved
* Add styles to .it-exchange-visual-cc to help it look more like a card
* Fix subtotal mis-alignment in content-cart elements and correct hook names in same template
* Fix for Wizard opening two tabs when clicking link for Membership addon and Stripe addon

= 1.7.25 =
* Added ability to get true product count from it_exchange_get_cart_products_count()
* Added fix for WP-Engine login requirements
* Remove image thumbnail div from products
* Remove extra space from bottom of advanced tabs on add/edit product screen

= 1.7.24 =
* Fixed issue with admin menu icons not functioning properly on sites that have an ABSPATH or WP_CONTENT_DIR of "/".

= 1.7.23 =
* Fix registration call for Cart and Checkout pages
* Fixed for Pages tab not showing Page Types set to WordPress or Disabled

= 1.7.22 =
* Removed extraneous 'Product' labels
* Added Text Domain to plugin Header block
* Added Order By product feature to Product's Advanced options and General Settings
* Fixed typo in Purchase Messages has_feature hook

= 1.7.21 =
* Fixed issue with admin menu icons not loading on sites set to use SSL while accessed via a non-SSL URL.

= 1.7.20 =
* Fixed typos in Cancel/Login Super Widget registration elements
* Fixed get_pages globals to work properly with Membership pages (and other add-ons)
* Fixed bug that caused slow product saves
* Setting email notifications class variables to public for developer add-ons
* Only init core shipping features if we have the shipping addon enabled

= 1.7.19 =
* Cache Casper Pages in GLOBALS to reduce load
* Create dummy post if none exist
* Replaced a join() with implode()
* Changed login redirect form to go to account page as it should
* Added some text to clarify the Account Page tooltip
* Removed some unused code from offline payments addon
* removed some uneeded code from admin user transactions view
* Changed how the view, refund, and transaction URLs are built on the admin user transaction view
* Adding a couple of filters to modify paypal button request and query request

= 1.7.18 =
* Added functionality to enable upgrades and downgrades with Membership add-on
* Blocking attachment pages for Exchange Downloads addons
* Break transient cache when a transaction is made
* Cache basic reporting get_transactions in transient
* Fixed type=url styling
* Remove 'is-featured' class from featured images being demoted on drop.
* Add 'is-featured' class to promoted featured image on drop
* Add min-height to image gallery thumbnails on add-edit product screens
* Product Gallery Modifications: - Generate unique IDs for list items instead of using image ID (allows image to be in list more than once) - When editing existing images, make clicked image already selected in Media Gallery when it opens. - When opening Media Gallery to edit an existing image, provide a way to actually save your changes.
* Fixed bad currency labels
* Change typo from 'Are you should' to 'Are you sure'
* Fixed error where resending email on payment status change for guest checkout didn't add name to email template
* Change the way checkbox and radio inputs are styled for the normal-sortables.
* Throw vars from parse_str into an array
* Added small top margin to transaction methods on the checkout page.
* Fixing the dice on the coupon add/edit screen. See: https://trello.com/c/XEbHEMen/896-coupons-coupon-dice-style-broken-in-3-8

= 1.7.17 =
* Edited ithemes shared resource

= 1.7.16 =
* Adding an JS hook API for exchange. Based on https://github.com/carldanley/WP-JS-Hooks
* Fixed products loop template action copy/paste error -- Thanks Ronald!
* Show all products in coupon dropdown
* Added a max-length option to the product description.
* Added some style mods for the colorbox popup.

= 1.7.15 =
* Bug Fix: Prior versions would fix non-https URL's for local content when the site was accessed via SSL so that the URL would become an https URL; however, it would not reverse the process and change https URL's to http when accessed without SSL. This caused problems on sites that use self-signed certificates and would sometimes have local content URL's that referred to the https location. This update makes the https URL's convert to http when the site is accessed via SSL.

= 1.7.14 =
* Added new action to protected pages method
* Fixed confirmation page bug caused when setting confirmation page as a WP page
* Fix bug where login link isn't switching to 'Log out' after login occurs
* Fix for bug causing Account variable to not be set when using WordPress pages for protected areas
* Fixed bug causing it_exchange_get_products to return empty when searching by product_type when only one product type is enabled
* Fix for placeholder/value when adding new products
* Added icon fonts as a registered stylesheet.

= 1.7.13 =
* Apply number_format to it_exchange_convert_from_database_number to get properly formatted prices that have decimals ending in 0 (which get trimmed)
* Edit Product page now remembers which advanced option you last selected
* Give rounding for coupons a higher precision
* Don't use theme API in lowerlevel product availability API
* Temp fix for vidembed plugin conflict.

= 1.7.12 =
* Disabled AJAX caching to deal with a bug in IE's aggressive AJAX caching
* Add filter to guest checkout to replace email address
* Don't print 'Available Downlowads' twice in confirmation email.
* Don't assume we have a WP User in email notification shortcodes

= 1.7.11 =
* Fixed bug that broke 3rd party calls to new WP_Query on product pages
* Added filter to disable the Buy Now button
* Fixed Product Type search meta key
* Fix for Screen Options not saving Products #
* Removed Product Purchases from sortable column list
* Pass prefix through transaction_number filter

= 1.7.10 =
* Add new WordPress Page Templates Core Add-on
* Add ability to filter any returned shortcode replacement for an email confirmation.
* Include current transaction details, current shortcode being processed, and the object for the email notification class.
* Add filters and attachments param to function that sends the confirmation email
* Added pre_query_posts action to remove hidden produts from product taxonomy queries

= 1.7.9 =
* Added Response Code to 'Invalid Response' message on downloads
* Added rounding function to discount to ensure it always rounds the same way
* Fixed bug causing error when removing all digital downloads from a product
* Fixed bug where hourly expiration on downloads wasn't working
* Changed URL used to init PayPal Secure and PayPal standard payments
* Changed hook that listens for download requests from template_redirect to wp
* Product Categories add JS working on add/edit products screen now
* Added simple grayscale to non selected payment types in wizard.
* Remove quick-edit from All Payments screen
* Added 12 actions to the Payment Details page
* Added filter to base price product theme api
* Added filters to preview and view product links
* Added filters to view / preview product button labels
* Apply cursor:not-allowed CSS rule to all external product types rather than to membership specifically.
* Added class in Wizard to distinguish between core and external product types.
* Removing blank localization string in categories so that packaging bot doesn't complain

= 1.7.8 =
* Fixing some internal submodules. WordPress.org version of Exchange jumpped from 1.7.3 to 1.7.8

= 1.7.7 =
* Initial Release Version

= 1.7.6 =
* Fix line height on remove download button.
* Fixing purchase quantity advance tab show/hide functionality
* Updating all screen_icon() functions to use ITUtility
* Fixing bug causing Product Categories widget dropdown to not work properly
* Fixing tooltip styling on shipping settings page
* Fixing HTML error in settings-form
* Remove margin on shipping method.
* Fixing it_exchange_number_format() function in javascript
* Add filters to Product Description and Product Description tooltip
* Fixed label misspelling on the wizard.
* Added Open Sans to the font stack.

= 1.7.5 =
* Initial Release Version

= 1.7.4 =
* Initial Release Version

= 1.7.3 =
* Pass current product to ajax script when checkout is clicked
* Refactor the tooltip
* Standardize the transaction details page styles.
* Add filter to Product Title label and tooltip on Add/Edit Product screen.
* Pass $description variable in existing description filter for Base Price on product Add/Edit screen.
* Changed user profile exchange label
* Removed some unused code
* Make template names filterable
* Fixing bug causing purchase notifications to be sent to the 'current user' rather thant he transaction's customer ID
* Added some actions for manual purchases to user products view
* Updated lib/classes

= 1.7.2 =
* Enhancement: Added ITUtility::screen_icon() to allow for easily preparing code for the WordPress 3.8 release. It only runs the screen_icon() function when WordPress is older than 3.8, thus avoiding the deprecation notice.
* Bug Fix: Removed Javascript notices created by the tooltips.
* Bug Fix: Removed Javascript notices created by ITDialog thickboxes.

= 1.7.1 =
* Add transaction object to admin_email filters

= 1.7.0 =
* Updated lib/icon-fonts
* Introduce MP6 changes for 3.8
* Add filter to store visibility value on add/edit product screen
* Added register script/style function to register all third party JS/CSS scripts that might be enqueued by addons
* Updated: lib/classes
* Added missing /div in coupons add/edit
* Change display name of add-on from 'Basic Coupons' to 'Coupons'
* Allow Coupons to be limited to a specific product.
* Added filter to create_posts capability in transation post type

= 1.6.3 =
* Enhancement: Improved output of ITUtility::print_r() in WordPress 3.8.
* Enhancement: ITUtility::print_r() now indicates the number of array elements in collapsed arrays and identifies boolean values explicitly.
* Enhancement: Added the ability for ITForm::add_drop_down() to show divided lists.
* Bug Fix: Fixed depth cutoff of ITUtility::backtrace().
* Bug Fix: Fixed broken javascript in error message output. This bug prevented the error message from being collapsed by default, causing the screen to show the message at all times.

= 1.6.2 =
* Don't show shipping address in Payment Details if transaction doesn't include shipping
* Convert Paypl Standard setting keys to be shorter - This was Chris's fault
* Don't hardcode sample product to digital downloads. Make sample product one of the product-types setup in the wizard
* Create Builder Views for all active product type's singular pages
* Replace preg_match with strpos in Builder Views integration
* Add action to rewrite rules method in pages class

= 1.6.1 =
* Update readme.txt
* Make buy-now theme API options filterable.
* Replace all instances of tertiary session_id logic with calls to it_exchange_get_session_id()
* Fix bug that caused incorrect shipping prices to be displayed on PHP versions before 5.4
* Remove 's from all Exchange Builder view descriptions
* Add Builder view for 'any exchange page'
* Add functionality to it_exchange_is_page() to retrun the current page if $page param was passed empty.
* Remove call to non-existant property in shipping-method Theme API class

= 1.6.0 =
* Introducing Guest Checkout
* Redirect back to Exchange Log in Page, not WP login page on failed log in
* Fix typo in customer confirmation email
* Fix bug that prevented Page settings from being saved if a page was previously set to 'disabled'
* Fix bug requiring a WP page to be selected before saving Page settings when page type is not WordPress
* Make default logout redirect go to login page if it isn't disabled. Go to site home if it is. Add filter to default.
* Prevent PHP error if remote_get returns WP_Error object when trying to retreive addons json from ithemes server
* Don't show quantity option in SW when changing coupon info
* Remove login link from above registration fields on checkout page
* Move login link below registration fields in SW and convert to button format
* Add 'core' tag to Simple Shipping add-on
* Init purchase dialog JS on SW non-AJAX load
* Large amount of tabbing and white-space corrections
* Decouple SW registration state login/cancel elements.
* Add breaks to switch statements in api/theme/login.php
* Updated our COOKIE key to work with some hosting environments
* Fixing paypal standard return code
* Add action to top of super widget ajax script
* Changing core template from "Logged in as:" to "Checking out as:" on Checkout page
* Cleaned up the image after zooming to prevent multiple images loading over and over.
* Removed margin and padding from images inside the product image popup.
* A couple product gallery fixes.

= 1.5.0 =
* Fixed some priority bugs
* Added additional IDs and classes to admin settings
* Added a general remove button style
* Added hooks for base price and customer pricing
* Broke out lib/templates/content-checkout/elements/purchase-requirements/logged-in.php to several more template parts for flexibility needed in Guest Checkout
* Updated the get-images function call to fix a bug
* Updated the Setup Wizard
* Modified the way the Logged-in purchase requirement determines which form to show (registration/login/options) so that we can filter it for Guest Checkout
* Added Default Checkout Form option to General Settings
* Added api method for saving billing address and defer to it from lib/cart/class.cart.php
* Added filter to existing save_shipping_address function
* Added conditional to update shipping/billing address API methods
* Added filter to require-user-login check before filtering file downloads
* Fixed call to wrong function in new confirmation page template part
* Added a couple is_object checks before get_class calls
* Introducing New Gallery

= 1.4.2 =
* Fixed typo in email notifications
* Fixed wizard styling for Stripe
* Added quick fix to margins
* Added hook to template loader
* Added tool-tips to admin form class
* Report 'Deleted Customer' when customer is missing
* Changed the class for the customer menu wrapper in the confirmation page

= 1.4.1 =
* Adding missing images

= 1.4.0 =
* Introducing Memberships
* Introducing Physical Products
* Introducing Simple Shipping
* Introducing Free Products

= 1.3.2 =
* Fix bug preventing Product details from showing if apply_filters was previously called
* Added some hooks to the customer API, fixed some typos
* Updated get-images to allow users to specify an specific image of a specific size.

= 1.3.1 =
* Fixed some i18n issues
* Added cancel links from the Paypal add-ons
* Fixed bug in Offline Payments for recurring, not keeping totals from parent transaction
* Added new class for quickly generating an admin setting form
* Added hooks to All Payments metabox in tranaction methods post type class
* Fixed border issue when first payment item in the wizard is selected.
* Added missing docblocks
* Fixed negative total and negative taxes
* Fixed bug with failed payments when multicart is deactivated

= 1.3.0 =
* Groundwork for upcoming Recurring Payments add-on
* Introduced Purchase Dialog API to allow transaction-method add-ons to invoke CC fields.
* Added optional Billing Address purchase requirement and associated core add-on.
* Added core add-on that enables store owner to switch product types.

= 1.2.1 =
* Introducing our Simple Product Type
* Add address-formats and measurement-formats data sets
* Tweak stripe upsell language now that it's free
* Create fallbacks for file delivery when allow_url_fopen and / or curl isn't available on the server
* Removed entry-title from the product-attribute wrap and added the class option.
* Fix template part comments in tax super widget template part
* Add ability for Store Owner to change 'Tax' label in settings.
* Change NL state to 'Friesland'
* Change default cancel link on cart from 'Cancel' to 'Edit Cart' on checkout page
* Add login, registration and cart links to login notification on checkout page

= 1.2.0 =
* Added base country and base state to settings page
* Added States data-set for US, AU, CA, ES, FR, NL, ZA
* Added countries data set
* Fix child theme url for functions.php include
* Added an indication of which fields are required for registration.
* Implementing Purchase Requirements API
* Added new method to api/theme/customers: display-name
* Added ability for 3rd Parties to hook into supwerwidget ajax.php
* Added .75em bottom margin to dashboard totals.
* Edited x visibility of the downloads list on the Add/Edit Product screen.
* Fixed small text input size for decimal and thousands separator.
* Fixed page settings input overlap.
* Added missing PHP break statements in api/theme/customer.php switch statements
* Added get_plugin_path publich function to IT_Exchange class
* Fixed a bug that causes the get-images array to only pull the last image and not all the images for a product.
* Allow themes to add functions.php to their /exchange folder
* Change product title from h1 to h2 in store view
* Fixed monthly transaction totals in reporting widget for PHP 5.2.
* Added transaction status to reporting widget
* Add more fonts to the add-edt product page font-family

= 1.1.3 =
* Updated lib/classes to version 2.3.5

= 1.1.2 =
* Added Duplicate Products core-addon
* Fixed but that redirected user to profile rather than back to checkout when asked to register before checkout out
* Fixed bug where activating Product Categories disables core Categories widget
* Fixed bug where permalinks have to be updated after changing product slug
* Fixed bug that throws PHP error when trying to call WP_Error->get_error_message()
* Fixed bug causing 0.00$ cost products to not display their price on the product details
* Fix bug preventing large files from being downloaded

= 1.1.1 =
* Updated lib/classes to version 2.3.4

= 1.1.0 =
* Fix broken confirmation page when set as a WP page type
* Simplifying versioning notification logic since we have a gazillion template-parts now
* Add a little more feedback to paypal error message
* Dequeue new styles and enqueue sw styles when deprecated templates are supported by the theme
* Temp fix for blank account page
* Change format of discount feedback on superwidget to not display updated total.
* Make sure we have an array before trying to loop it - Paypal Standard Secure
* Fix error where template file name is printing at bottom of shortcode pages.
* Adding Simple Taxes core add-on
* Corrected typo in PayPal Secure Wizard settings
* Fixed bug that made downloads not show on the downloads page.
* Add theme_support option for deprecated-template-parts

= 1.0.3 =
    Add slash to itExchangeSWAjaxURL to fix login/registration bug.
* Add default error message to login SW Ajax when WP_Error returns an empty message.
* Reordered addon_init to prevent 3rd party addons from being included twice
* Add filters to preserve product types on Exchange Reset
* Changed the way user login and registration AJAX works in the superwidget, needed for extendability e.g. MailChimp (coming soon)
* Removed the styles from the WordPress update nag.
* Fixed theme api filters
* Added email category type for add-ons

= 1.0.2 =
* Fix typos in content-downloads.php and email confirmation.
* Changed Video links to target _blank
* Various readme.txt typo fixes
* Add Notice when our default template parts get updated
* Fixed bug not allowing inventory setting to be saved in some instances
* Added new shortcode for email templates: login_link
* Change default state to Registration, not Login, when user tries to access checkout while not logged in.
* Fixed unconverted nbsp
* Fixed mistyped localization namespace
* Updated copy in Get More top description
* Updated the Dashboard Reporting Widget for when there are no sales yet, per Brad's trello card
* Modify coupon limit fields
* Add coupon limit to Basic Coupons add-on
* Fix bug preventing subpages of store and account from working correctly
* Remove Log Out page from showing up in WP's Appearance --> Menus

= 1.0.1 =
* Fix some spelling errors in api/addons.php
* Fix bug that allowed users to create transactions manually in WPMS
* Whitelist additional file types for upload on the Exchange Add/Edit Product page
* Jonathan Davis attribution for it_exchange_parse_options() and at top of api/theme.php
* Fixed an issue where the Replace featured image text is hidden.
* Fixed a bug in the add/edit product page that cause the advanced inner panel height to not coincide with the height of the tabs

= 1.0.0 =
* Initial commit at wordpress.org

= 0.4.22 =
* Remove ithemes licensing, updater code. BETA testers won't receive another update until we push 1.0.0 to wordpress.org SVN

= 0.4.21 =
* General cleanup of the Super Widget styles.
* Updated copy for PayPal Standard Basic and Secure
* Updates some styles for the Wizard.
* Updated the images for Paypal options on wizard.
* Moved Paypal testing mode options to the bottom
* Added more indication that the editing button text for Paypal was present and optional.
* Changed titile to title on confirmation template.
* Fixed typos on confirmation template.
* Updated PayPal add-on names used on add-on page. Also updated description of Secure add-on

= 0.4.20 =
* Fix bug that didn't delete posts with stati set to not return in searches when reseting Exchange
* Added custom PayPal Standard (insecure/secure) button functionality
* Fix autop in extended description
* General admin styles cleanup.
* Increased the font size for the p on the add-ons screen.
* Added setup page to is_exchange_admin_page() to add it-exchange-admin class to body.
* Fixed webhook problem with two paypals
* PayPal Standard non-Secure
* Fix bug that showed customers other's transactions / downloads
* Escape bloginfo( 'name' ) calls better.

= 0.4.19 =
* Set with_front to false for product rewrites
* Remove extra slash from View All link in reporting dashboard widget
* Add Purchase Message to confirmation emails
* Fix bug preventing Product Availability from saving if date_format started with day.
* Update plugin description to Easily sell your digital goods with iThemes Exchange, simple ecommerce for WordPress
* Fix incorrect coupon label in shopping cart
* Fix PHP error related to currency symbol
* Added some reformatted styles to the product price.
* Moved the optional Paypal Sandbox setting to the end of the form.
* Updated readme.txt
* Increased font size for the h4 headings on the wizard.
* Fixed paypal setting variables in transaction processing
* Removed link in Wizard tooltip that should not have been there.
* Convert the currency to a number based format on focus out of the input field
* Removed rogue HTML link (displayed as plain text) to iThemes.com in a tooltip in the setup wizard.
* Cleaned up formatting of the payoption buttons in the setup wizard.

= 0.4.18 =
* Add stripe image to uninstalled stripe select box in wizard
* Add H3s back to wizard for paypal and offline payments
* Cleaned up the wizard styles.
* Add default width to 80px for checkout images
* Add video link to offline payments settings
* Remove utility script committed by accident
* Add links to paypal dev api tutorials in links
* Fix for escaping issues with blogname when setting default value for company-name.
* PDT instructions in PayPal, just a little clearer
* Removed much of the advanced data from the product page (expiration, limits, downloads, et cetera).
* Update video link for PayPal
* Made the response message more prominent when updating a payments status.
* Hid the status update section if js is not enabled.
* Fixed get-more-addons view to properly look for the add-on icon
* Break page settings cache before flushing rewrite rules
* Update to transaction methods to save state on errors in wizard
* Move Documentation, Support, and Add-ons links from first column in plugins page to second column
* Change Wizard save button text to 'Save Settings'.
* Redirect to wizard after saving, not to Add new product.
* Convert wizard error/notice messages to messaging API to preserve on redirect.
* Add new saved notification message to include links to New Proudct, Addons, Sample Product.
* Changed paypal description to be cart description, not cart name
* Remove autop when using exchange templates.
* Fixed remaining typos in instructions and tooltips
* Disable unchosen transaction methods in wizard
* Added some filters and changed some function names in the transaction methods

= 0.4.17 =
* Typo Updates: 1-13 of 39
* Wizard selects transactions methods that are already enabled now (step 1)
* Add it-exchange-admin to body class of all admin pages that are exchange related
* Added some styles to the settings pages.
* Require users to have capability to activate_plugins (admin) to see Reporting dashboard widget. Capability is filterable
* Fixed superwidget
* Move Settings, Add-ons, Help to separate function so we can push them further down the submenu list.
* Rename product category and product tag add-on slugs so that they appear next to each other in Add-ons
* Update registered add-on categories to reflect what we used in core
* Added URLs to help page.
* Added styles to the Exchange admin help page.
* Final links in help page
* General template cleanup and localization.
* Fix typo in reporting widget
* Updated more links
* Remove stripe from core
* Add tabindexes to Product File fields on add/edit product screen
* Rename readmee.text to readme.txt
* Changed CSS padding for transaction method selections in Wizard
* Replaced dummy links in plugins action row
* Fix foreach PHP notice in Product Availability metabox.
* Fix bug causing product end availabilty request in theme API to return the start date
* Apply autop to extended-description

= 0.4.16 =
* Add tooltip to Product File source to explain that they can paste URLs from other sources
* Fixed bug where download API was passing wrong param to function
* Fixed bug found by glenn in availability
* Change Files to Product Files in add/edit product screen.
* Fix several typos
* Don't create more than 1 sample product if admin goes back to wizard and saves again
* Store availability dates as epoch, pull them out as WordPress dateformat
* Activate Exchange Menus by default
* Fixed decimal separate issues in base price and coupon amounts, this will require all existing installations to reset exchange data
* Added MP6ish styles to the error and update notifications on the Exchange dashboard (staying ahead of the curve).
* Add .org readme.txt
* Add sample product when wizard is saved.

= 0.4.15 =
* Wizard-addon.png option now allowed and working...
* Add register addons action. Switch core addons to use this action
* Fixed bug allowing wizard saving successfully when stripe is selected (but the addon isn't activated)
* Styled up the email notifications (as much as possible).
* Fixed issue with feature image not being saved properly when moved around
* Fixed issue with last image not being removed upon update
* Fixed the x on the product page.
* Added missing docblocks
* Wizard settings now pass through error message for failed transaction method setup attempts
* Fixed issue with cover moving when scrolling.
* Added tooltips to transaction details.
* Remove wizard margin when screen options are not available
* Message styles are now more consistent.
* Added processing payment notice when purchasing with Stripe.
* Fix bug where updating Settings --> Pages deleted non-Exchange custom Links in the WP Nav API
* Prevent duplicate slugs from being saved on Pages tab in settings.
* Fix false positive for emty slug error on Pages tab in settings.
* Fixed bug allowing users to 'start selling!' without selecting a valid payment method
* Finished all @todos in the code that we're probably going to do before launch
* Fixed quantity bug
* Replace session_id() with $session_id retrieved from db-sessions class in nonces
* Added documentation link to plugin screen
* Mutliple @todo updates. Largely validations.
* Added/modified tooltips based on feedback from Kristen and Elise.
* Enabled hide/show functionality in Stripe and PayPal settings for test modes.
* Added row action to plugin for quick setup, documentation, support, and add-ons
* Replaced Stripe, PayPal, and default Add-ons icons
* Add tooltip to transaction details page
* Fixed max quantity issue when purchasing products
* Added styles for the transaction details status changed and changed message to Saved or Not Saved.
* Enabled tooltips for the pages settings.
* Cleaning up @todo messages we left ourselves. Added several error messages and notices throughout code.
* Force registration page type to 'disable' if using WP registration settings and WP registration is off, Added tooltip to explain this.
* Finished cleaning up the templates.

= 0.4.14 =
* Add descrption to postslug div
* Fix broken div in inventory metabox
* Changed markup and styling of Single Product page template
* Remove Featured Product and Cart Summary code from core
* Remove 'product-supports' options from addon registration requirements for transaction details
* Clean up Product Availability metabox fields
* Remove Transaction Status metabox. Replaced with AJAX update status earlier this week
* Confirmation Email modifcations
* Localize strings on help page
* Use exchange logo on help page
* Standardized addon settings pages. Maybe made them look a tiny bit prettier.
* Cory's Wish List :) -- 1) added a bunch of tips, 2) Updated Pages to include  'tips' data, 3) fixed some strings that weren't i18n
* Empty addon tab messages
* Always enqueue SW JS in product super-widgets
* Changes to superwidget to handle processing payment popup better
* Change single-product-super-widget class name
* Add featured image to theme API for transaction products.
* Add featured image call to /lib/templates/content-purchases.php
* Fix bug that prevent SW stying from enqueuing when embeded in product template
* Change default Exchange permissions from read to activate_plugins (this is filterable)
* Added processing dialog to stripe payment upon submit
* Change log_in template part to login
* Modifying version var and history.txt after packaging bot did its thing
* Fix to quantity to pay attention to current context of current super widget
* Changed coupon field to work on submit, not just button click
* Update inventory when purchases are made
* Standardize docblocs in default templates.
* Added max value to the item quantity to prevent the iterator from exceeding the max quantity for that item.
* Styled up the dashboard widget.

= 0.4.13 =
* Updated lib/classes to version 2.3.3

= 0.4.12 =
* Remove stylesheet settings from Main settings. Add filters for not enqueuing stylesheet: it_exchange_disable_frontend_stylesheet, it_exchange_disable_super_widget_stylesheet
* Applied CSS to coupons section of Super Widget.
* Added registration styles to the super widget.
* Fixed the hover jump on featured image.
* Advanced <label> corrections
* Added the feature-image to the checkout template.
* Changed currency unicode characters to their HTML entity equivalent.
* Remove transcation page from WP menu UI
* Add Featured Image and Product Images to cart-item API
* Remove PHP strict warning when products are trashed
* Added message to Store template if no products are found
* Fix bug preventing save of custom stripe button text from wizard
* Remove superwidget class from non-superwidget login form
* Multiple spelling corrections in product feature meta boxes
* Fix multiple bugs that cause Exchange to explode if someone disables the store page or uses a WordPress page for store or account
* You can now get all the images (with all registered image sizes) for a product.
* Modified stripe purchase button to use class instead of ID so Stripe functions normally when two buttons appear on a page (even if the others are hidden)
* Fix bug where visibility meta_query was overwriting disabled product meta_query
* Bounce customers who directly access disabled product type single URL to the store.
* Bounce users away from admin screens for products belonging to Disabled Product Types
* Added missing docblock from zero-sum-checkout, I think someone else already added a bunch anyway
* Removed !multi-cart requirement for registration/login/etc in SW... these are needed for multi-item carts that only have one items
* Update itExchangeIsUserLoggedIn in JS when logging in is successful
* Product Tag JS/AJAX now working on Product Edit page
* Move SupwerWidget CSS to its on file.
* Provide ability to disable default Exchange theme CSS in settings (non SW).
* Provide ability to disable default Exchange SW CSS in settings.
* Add details about custom stylesheets in settings.
* Add heading titled 'Dangerou
* Modified product content to output the super widget, not just the purchase options, definitely important for single item carts
* If parent theme exists and has /exchange/style.css, enqueue it after exchange styles.
* If child theme is different than parent theme and has /exchange/style.css, enqueue it after exchange and parent styles.
* Delete purchase quantity value when left blank while editing.
* Get purchase quantity when on edit screen even if not enabled to preserve setting
* Add hook that gets called after our product screen layout is setup

= 0.4.11 =
* Fixed Dashboard menu Add Product entry so that it is highlighted when on that page.
* Fixed Dashboard menu Product Categories and Product Tags entries so that the Exchange menu expands when on those pages.
* Fixed Upload link position on the Download Source on the Add/Edit Product Screen.
* Fixed bug where super widget error/notice messages were inheriting styles not intended for them
* Fixed bug where advanced section item's inner height was not getting set correctly.
* Fixed a bug with the checkboxes on the add/edit product screen.
* Fixed function name typo: changed it_exchange_basic_coupons_remove_submeu_links to it_exchange_basic_coupons_remove_submenu_links.
* Added some styles to the empty cart state.
* Added a few resets to the gallery.
* Adds Error/Notice Message styling
* Dump sessions when multi-item cart is enabled.
* Update to Store Template
* Styling for Store template
* Update to Store template
* Update to the product gallery and featured images
* Fix typo in theme API for downloads
* Fixed issue where enabling/disabling an Add-on from the All tab in Settings > Add-ons caused the All tab to be inactive.
* Don't enqueue coupons if screen object is missing.
* Added initial Store template a couple markup changes to Product template
* Fixed how the "Notification Email Template" label in Settings > Email Settings pointed to the input for "Email Template".
* Forced the $price passed to it_exchange_format_price to 0 if it is not numeric. This removes a warning on the All Products listing if an empty string was saved as the price.
* Added hide-if-super-widget CSS class/functionality, so purchase options can appear on product page with no super-widget enabled
* More product gallery awesomeness.
* Remaining localization for JS
* JS localization for add/edit products
* Fix for product refresh removing item from superwidget for single-item carts
* Pushing up changes to the product gallery.
* Remove no-debug query arg from SW Ajax calls
* Modifying the quantity JS/AJAX
* Moving coupon output outside of cart-item while loop
* Removing debug code
* Fix bad labels for Product Slug and Purchases on Settings --> Pages tab
* Prevent Page Settings from saving if page is WordPress type but has no WordPress page selected
* Fix for coupons input not appearing when no coupons added
* Fix for quantity issue in SW / single item cart
* Fix strict warning on Settings --> Pages tab
* Change unlmited purchase quantity feedback in theme API for products from 0 to 'Unlimited' by default.
* Fix bug preventing deletion of all sessions when Exchange Reset option is checked
* Fix missing exipraiton and download limit theme API functions
* Setup MailChimp form submission on get-more-addons page
* Fix menus error for WP version 3.5.2
* Resend customer email when a transaction status is updated from not cleared to ship to cleared to ship.
* Allow transaction methods to register ability to manually change transaction status.
* Add ability to change transaction status to bottom of transaction details if allowed by transaction method.
* Set return to addons link to only show on add-on settings page... was showing on wizard in some cases
* Added filters for modifying purchase notification email templates
* Check get e-mail updates from us about iThemes Exchange automatically
* Hide test/sandbox mode fields on wizard
* Remove static call to non-static method in Stripe add-on

= 0.4.10 =
* Don't print download links on Confirmation page or Downloads page if transaction is not cleared for delivery fixed default state issue
* Added it_exchange_is_current_product_in_cart() to check if current product being viewed is in the cart already
* Added view_cart() to output a View Cart button on the SW (or anywhere else)
* Fixed log-in to log_in for casper
* Don't include file links in email if the transaction hasn't been cleared for delivery.
* Reformatted the pages settings page to work with the workflow and styles of @brad's mockup.

= 0.4.9 =
* Updated lib/classes to version 2.3.2
* Set defaults before asking for download setting in the event that admin hasn't visited settings page.
* Auto-enable Basic Reporting when Wizard is saved
* Add Basic Reporting Widget as a core add-on.
* Added function to lib/functions/functions.php that allows us to restrict any it_exchange_get_[products|transactions|coupons|downloads|etc] to a date span
* Add 'Add Product', 'View Product', and 'Edit Product' to WP Admin Bar
* Fix but where enabled plugins were being returned by it_exchange_get_disabled_plugins()
* Fix bug where template parts were not loading correctly from directories outside of exchange/lib/templates
* Create new template part for store-product

= 0.4.8 =
* Remove transaction from page settings tab
* Missing space? What missing space?
* Changed the product images output and fixed the product feature-image call.
* Added cancel link to login, fixed empty_cart functionality in JS/AJAX
* Don't load capser on product pages. Oops
* Cleaned up product images HTML output and added ability to remove featured image.
* Replace missed Router reference with Pages. Fixes missing product information on single product views.
* Removed slide for advanced tabs.
* Added tooltip to downloads limit and expiration labels.
* Make shortcodes work on WP type pages.
* Rename routes to pages and class.router.php to class.pages.php
* Change nav menu URLs when switching from exchange page type to wordpress or vice-versa
* Fix login/logout vars in it_exchange_wp_get_nav_menu_items
* Break page cache when building nav menu items
* Return WP url if page type is set to 'wordpress'
* Don't load WP slug and name on settings page
* Don't load casper if page type is not 'exchange'
* WordPress Pages as options
* Fix bug related to identifying subpages of account page
* Cancel link on registration template for superwidget now works
* Fixed log_in redirect to profile page.
* Renamed log-in.php template to log_in.php because IT slug changed from - to _
* Working on registration cancel button
* Tweaks to the version var and history after packaging bot did its thing.

= 0.4.7 =
* Updated lib/updater to version 1.0.2

= 0.4.6 =
* Fix spelling of acquired in get more add-ons blank view.
* Get more add-ons view: make contact form button open in new window.
* More transaction details tweeks.
* Buy-now button/add-to-cart button displaying properly for multi-item-cart/single-item-cart
* Added some classes to help me troubleshoot more
* Added company name default
* Cleaning up the transaction details (removing product download hashes and styling the refunds).
* Fix product rewrite slug i hosed with new page API
* Make it possible to filter pages by type in it_exchnage_get_pages()
* Fix bug introduced with new page API that was preventing the SW from showing up on product pages.
* Don't delete superwidget on Exchange Reset.
* Delete posts regardless of post status in Exchange Reset.
* Delete sessions in Exchange Reset.
* Don't print dropdown on Page Settings screen if only one type is available.
* Don't print shortcode for Products
* Check for array indexes before grabbing value from them in api/pages.php
* Put all needed elements in place an Page Settings page.
* Save and update new page settings
* Introducing it_exchange_register_page() and supporting casts.
* Starting work on updated Settings --> Pages screen.
* Remove product(s) from cart summary and replace with product/products based on count
* If multi-item cart is enabled and user hits Add-to-Cart, load the cart state if not logged in but load the Checkout state if logged in.
* Fix bug where I was forcing login checks for cart instead of checkout by accident
* Cart and Checkout should be subs of store, not account in get_page_url().
* Fix option keys for hiding quantity field in SW product template
* Added some styles to the add-on settings screen.
* Removing my browsing state from the SuperWidget
* Fixed coupons styles and javascript bug.

= 0.4.5 =
* Adjusted line height on product description.
* Added some styles to the messages on the super widget.
* Adjust add-ons activate buttons style.
* Added download title name automatically if title is empty when entering WP Media Gallery.
* SuperWidget CSS Tweaks
* Fixed item-count bug in SuperWidget cart
* Added color to text on super widget
* Enqueue basic_coupon scripts in addon code, not core code
* Fixed edit-quantity invalid index in product.php theme API
* Added admin notification email customization on Email settings
* Added 'back to add-ons' link for add on settings pages
* Fixed erroneous validate filter call for addons
* Allow store owners to remove requirement for users to log in before downloading their products
* Fixed tabbing issue on Products page
* Changed it_exchange_is_addon_installed() to it_exchange_is_addon_registered()
* Renamed function clean_it_exchange_query_args() to it_exchange_clean_query_args()
* Show available core transaction methods inside wizard.
* Activate transaction methods on wizard save
* Style Get More Addons tab when empty

= 0.4.4 =
* Removed lib/api/class.api.php
* Renamed it_exchange_is_view() to it_exchange_is_page()
* Added it_exchange_get_page_slug()
* Added it_exchange_is_page_ghost_page()
* Remove 'Add to cart' option when max quanity has been reached.
* Use esc_attr_e on page URLs on admin Page Settings tab.
* Move page related functions from api/misc.php to api/pages.php
* Added additional margin to the wizard nag to avoid collision with Screen Options and Help tabs.
* Reset customer menu padding and margin.
* Make Product Images and Product Descrition even on Add / Edit products page.
* Added a tabindex to the normal sortable items
* Removed some unneeded code from the add-edit-product.js file.
* Add new API file: api/pages.php.
* Add new function it_exchnage_get_pages()
* Replace all instances of it_exchange_get_option( 'settings_pages') with it_exchange_get_pages()
* Fixed Delete Download button not appearing properly for existing downloads
* Fixed purcahse typos
* Do not load SuperWidget JS if SuperWidget is not active
* Removed admin reports from Page Settings
* Modified PayPal button
* Remove exchange.php from valid template names to look for in locate_template function.
* Don't look for exchange template files in root theme or root themeparent folders (only in themefolder/exchange)
* Added stripslashes to PayPal button output.
* Dont't redirect non-admins to /store after checkout

= 0.4.3 =
* Fix bug where first post humbnail showing up on random pages
* Differentiate between live-mode and test-mode for Stripe IDs, to prevent 'No such customer' errors when switching between the two
* Removed uneeded customer data description text
* Fixed stripe company name error
* Added column for order number to transactions tab of customer info
* Removed error_log() call in downloads class
* Filter out products from disable product types on All Products screen.
* Remove several functions not needed anymore.
* Change privew button to View and Save when product has already been published
* Auto-enable all non-core add-ons
* Don't register add-ons more than once
* Make Disable link for non-core add-ons point to plugins.php page
* Modified router for is_product to work to view drafts
* Squash bug where email defaults aren't available to product notification if email page hasn't been saved.
* Add filter to RESET ALL settings array so admin can filter out some settings from being reset
* JS alert to confirm Exchange data reset
* Add new filters for theme API:
* * it_exchange_theme_api
* * it_exchange_theme_api_{tag}
* * it_exchange_theme_api_{tag}_{method}

= 0.4.2 =
* Add ablity to customize Stripe 'Purchase' button text
* Add ability to close Wizard nag
* Add feedback when coupon is applied (or isn't applied)
* Auto-enable Digital Downloads Product Type when Wizard is saved
* Add setting to bottom of General Settings page that deletes ALL DATA. Only shows up if WP_DEBUG is defined as true
* Add coupons icon to all coupons screen
* Add placeholder in Add/Edit product Currency field.
* Fix error where prices with commas, currency symbols don't save correclty when adding products.
* Fix PHP error on offline-payment checkout.
* Add transaction cleared for delivery hook to offline payments
* Add transaction is cleared for delivery hook to zero_sum_checkout
* Add transaction_is_cleared_for_delivery hook to paypal_standard
* Fixed but in it_exchange_get_transaction_status.
* Added function to return when Stripe transactions are valid for delivery.
* Prevent downloads from happening if transaction is not valid for delivery.
* Add ability to only return transactions cleared for delivery when requesting all transactions tied to a product
* Add purchase count to all products 'Purchases' column
* Remove false warning about incorrect currency for Stripe
* Removed admin.php, not being used/called
* Add loads of filters and actions in api/ functions

= 0.4.1 =
* Remove zero-sum transaction from wizard
* Admin icons

= 0.4.0 =
* All the things since 0.3.10
* Excluding Packging Bot updates
* Private Beta

= 0.3.12 =
* Updated lib/classes to version 2.3.1

= 0.3.11 =
* Updated lib/classes to version 2.3.0

= 0.3.10 =
* Standardized all form fields with hyphens and WP hooks with underscores

= 0.3.9 =
* All your CartBuddy are belong to Exchange

= 0.3.8 =
* Customer Class / API
* Folded cart into Core
* Folded WP post supports into core
* Restricted Content / Membership Add-ons
* Updated lib/classes to version 2.2.0

= 0.3.7 =
* Use ITStorage2 for settings
* Use ITForm for admin forms
* Form validation / feeback for admin settings
* Add-on Settings API
* Transaction Methods API
* Storage API
* Cart API
* Default Cart Add-on
* Refactored Sessions API
* Offline Add-on
* Standardized function names accross codebase
* Customer Mangement API (WIP)
* Messaging / Errors API
* EVERYTHING IS STILL VERY MUCH IN PROGRESS AT THIS POINT

= 0.3.6 =
* Updated lib/classes to version 2.1.9

= 0.3.5 =
* Admin General Settings
* Admin Email Settings

= 0.3.4 =
* Updated lib/classes to version 2.1.8

= 0.3.3 =
* Hooks for Product, Transaction create, update
* Add-on Supports API
* Transaction API
* Add-on: Transaction Status Metabox

= 0.3.2 =
* Introduced Product class
* Refactored enable / disable add-ons functionality
* Introduced required / default meta_data to addon categories, add-ons, and product post_types

= 0.3.1 =
* Item Type bug fixes. DocBlock @since fixes
* Remove class_exists from it-exchange.php
* Change admin addon param to product-type
* Add product_type to object and post_meta
* Rename Items to Products. Rename files, vars, labels
* Include add-on files when enabled
* Add core Product Type Metabox Addon
* Modify Edit Post label to reflect Product Type being Edited
* Make sidebar admin menu open to Exhange on Edit Product screen

= 0.2.0 =
* API Revamp

= 0.1.0 =
* Proof of Concept

== Upgrade Notice ==
= 1.35.11 =
Fixes a serious security issue. Upgrade immediately.

== Screenshots ==

1. Quick Setup
2. Add New Digital Product
3. Add New Physical Product
4. Add-ons
5. Add Coupon
6. Customer Detail
7. Dashboard Widget
8. Payments
9. Email Settings
10. Pages Settings
11. Help
