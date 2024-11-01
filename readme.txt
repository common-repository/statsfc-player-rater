=== StatsFC Player Rater ===
Contributors: willjw
Donate link:
Tags: widget, football, soccer, player, rater, premier league, fa cup, league cup, champions league, europa league, uefa
Requires at least: 3.3
Tested up to: 6.2.2
Stable tag: 2.0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This widget will place a player rater for all matches of any Premier League team on your website.

== Description ==

Add a player rater for any Premier League team's matches to your WordPress website. To request a key sign up for your free trial at [statsfc.com](https://statsfc.com).

For a demo, check out [wp.statsfc.com/player-rater](https://wp.statsfc.com/player-rater/).

= Translations =
* Bahasa Indonesia
* Dansk
* Deutsch
* Eesti
* Español
* Français
* Hrvatski Jezik
* Italiano
* Magyar
* Norsk bokmål
* Slovenčina
* Slovenski Jezik
* Suomi
* Svenska
* Türkçe

If you're interested in translating for us, please get in touch at [hello@statsfc.com](mailto:hello@statsfc.com) or on Twitter [@StatsFC](https://twitter.com/StatsFC).

== Installation ==

1. Upload the `statsfc-player-rater` folder and all files to the `/wp-content/plugins/` directory
2. Activate the widget through the 'Plugins' menu in WordPress
3. Drag the widget to the relevant sidebar on the 'Widgets' page in WordPress
4. Set the StatsFC key and any other options. If you don't have a key, sign up for free at [statsfc.com](https://statsfc.com)

You can also use the `[statsfc-player-rater]` shortcode, with the following options:

* `key` (required): Your StatsFC key
* `team` (required): Team name, e.g., `Liverpool`
* `competition` (optional): Competition key, e.g., `EPL`
* `date` (optional): For a back-dated match, e.g., `2013-12-31`
* `hide_average` (optional): Hide average ratings until a user has rated, `true` or `false`
* `default_css` (optional): Use the default widget styles, `true` or `false`
* `omit_errors` (optional): Omit error messages, `true` or `false`

== Frequently asked questions ==



== Screenshots ==



== Changelog ==

= 2.0.0 =
* Refactor: Update plugin for new API

= 1.15.4 =
* Hotfix: Minor JS bug

= 1.15.3 =
* Hotfix: Possible issue loading language/CSS files

= 1.15.2 =
* Hotfix: Check options exist before using them

= 1.15.1 =
* Hotfix: Check the before/after widget/title bits exist before using them

= 1.15.0 =
* Feature: Added `restricted` parameter, which allows the average ratings to be restricted to your own site rather than a global average

= 1.14.§ =
* Hotfix: Load relevant language file based on the default language for the site

= 1.14.0 =
* Feature: Added multi-language support. If you're interested in translating for us, please get in touch at [hello@statsfc.com](mailto:hello@statsfc.com)

= 1.13.1 =
* Hotfix: Added a responsive horizontal scroll if the widget is too wide for mobile

= 1.13.0 =
* Feature: Added `hide_average` parameter, which allows average ratings to be hidden until a user has rated

= 1.12.1 =
* Hotfix: Fixed possible `Undefined index: omit_errors` error

= 1.12.0 =
* Feature: Put CSS/JS files back into the local repo
* Feature: Enqueue style/script directly instead of registering first

= 1.11.0 =
* Feature: Added `omit_errors` parameter
* Feature: Load CSS/JS remotely

= 1.10.2 =
* Hotfix: Fixed "Invalid domain" bug caused by referal domain

= 1.10.1 =
* Hotfix: Fixed bug with multiple widgets on one page

= 1.10.0 =
* Feature: Converted to JS widget

= 1.9.0 =
* Feature: Allow more discrete ads for ad-supported accounts

= 1.8.0 =
* Feature: Include substitutes, where available

= 1.7.0 =
* Feature: Added a `competition` parameter

= 1.6.0 =
* Feature: Set a reasonable width for the drop-downs

= 1.5.0 =
* Feature: Enabled ad-support

= 1.4.0 =
* Feature: Use built-in WordPress HTTP API functions

= 1.3.0 =
* Feature: Default `default_css` parameter to `true`

= 1.2.0 =
* Feature: Added `[statsfc-player-rater]` shortcode.

= 1.1.0 =
* Feature: Added a `date` parameter.

= 1.0.2 =
* Hotfix: Fixed a cookie bug.

== Upgrade notice ==

