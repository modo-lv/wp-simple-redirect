# Simple Redirects (plugin for WordPress)
A fork of Scott Nellé's "Simple 301 Redirects" WordPress plugin.

## Changes
* Redirects work regardless of address used (i.e., will work on both "domain.com" and "www.domain.com" if the wordpress itself works on both).

## Installation
* Deactivate and/or remove "Simple 301 Redirects" plugin if you have it activated.
* Create a `wp-simple-redirects` folder in `wp-content/plugins` and place `wp-simple-redirects.php` in there.
* Activate the plugin from admin panel.

## Compatibility
* Plugin configuration is 100% compatible — you can switch between the original plugin and this one at will.
* This plugin **can not** run at the same time as the original, because an address cannot be redirected to two addresses. So make sure that either this plugin or the original is active, but not both.

## Credits
* Original plugin: http://www.scottnelle.com/simple-301-redirects-plugin-for-wordpress/