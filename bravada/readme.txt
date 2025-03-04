=== Bravada ===

Contributors: Cryout Creations
Requires at least: 4.5
Tested up to: 6.6
Stable tag: 1.1.4
Requires PHP: 5.6
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl.html

Copyright 2020-24 Cryout Creations
https://www.cryoutcreations.eu/

== Description ==

Bravada - the name says it all. It's a theme that's not afraid of anything. It will look amazing, behave flawlessly and scale to any screen. It goes anywhere, it's for everyone and everything. It's clear, clean and simply gorgeous. It has CSS powered animations that will bring users to their knees. Being designed as mobile-first, it's as responsive as you'll ever get. Being highly customizable, it comes with a plethora of options that will truly make it your own while still being extremely easy to use. Google fonts are supported, but you can also use your own fonts if GDPR is giving you trouble. You can dynamically change every aspect of your fonts for many site elements (size, line height, font styles, etc.) Colors are also editable and, if you want, you'll have a great time making your own color schemes. You have multiple layouts to choose from, the site, content and sidebar widths are also customizable, magazine layouts with masonry are enabled by default, but you can also edit those. Metas like author, date, tags, categories and comments are toggleable, you can decide which ones to show on blog pages and which ones to show on single pages. Widget areas galore, place your widgets almost anywhere you want, the theme doesn't discriminate. And then there's a fully customizable landing page with icon blocks, featured boxes, text areas and a slider (you can use our own or paste in a shortcut from any other slider). We also thought about socials and you can choose from a seemingly countless number of socials to populate your site with. Gutenberg blocks? They feel right at home in our theme! Of course it's also translation ready and Right To Left (RTL) languages are fully supported out of the box. WooCommerce feels right at home with our theme, we've taken all measures to seamlessly integrate it. Oh, and just like with our other themes, the updates will keep on coming, constantly improving and keeping it relevant for years to come. Bravada is a theme for all types of sites out there: blogs, businesses, presentation or photography sites, news or portfolio sites. There are no limits - there is only Bravada.

== License ==

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see http://www.gnu.org/copyleft/gpl.html


== Third Party Resources ==

Bravada WordPress Theme bundles the following third-party libraries and resources:

TGM Plugin Activation
Copyright Thomas Griffin, Gary Jones, Juliette Reinders Folmer
License: GPL-2.0 or later license
Source: https://github.com/TGMPA/TGM-Plugin-Activation

HTML5Shiv
Copyright Alexander Farkas (aFarkas)
License: Dual licensed under the terms of the GPL (https://www.gnu.org/licenses/gpl-3.0.en.html) and MIT (https://opensource.org/licenses/MIT) licenses
Source: https://github.com/aFarkas/html5shiv/

FitVids
Copyright Chris Coyier - http://css-tricks.com + Dave Rupert - http://daverupert.com
License: WTFPLlicense
Source: http://fitvidsjs.com/

prepareTransition
Copyright Jonathan Snook
License: MIT license
Source: https://snook.ca/archives/javascript/preparetransition-jquery-plugin

== Bundled Fonts ==

Icomoon icons
Copyright Keyamoon.com
License: GPL license, https://www.gnu.org/licenses/gpl-3.0.en.html
Source: https://icomoon.io/#icons-icomoon

Entypo+ icons
Copyright Daniel Bruce
License: CC BY-SA 4.0 license, https://creativecommons.org/licenses/by-sa/4.0/
Source: http://www.entypo.com/faq.php

Feather icons
Copyright Cole Bemis
License: MIT license, https://opensource.org/licenses/MIT
Source: https://feathericons.com/

Zocial CSS social buttons
Copyright Sam Collins
License: MIT license, https://opensource.org/licenses/MIT
Source: https://github.com/smcllns/css-social-buttons

Bootstrap Icons
Copyright The Bootstrap Authors
License: MIT license, https://opensource.org/licenses/MIT
Source: https://icons.getbootstrap.com/

== Bundled Images ==

The following bundled images are released into the public domain under Creative Commons CC0:

Header and screenshot image, Copyrigh Simon Migaj
License: CC0 1.0 Universal (CC0 1.0)
Source: https://stocksnap.io/photo/landscape-man-NXJPTEG0WP

The rest of the bundled images are created by Cryout Creations and released with the theme under GPLv3.


== Changelog ==

= 1.1.4 =
*Release date: 2024.10.03*

* Added banner/slider background color option (for Ripley child theme)

= 1.1.3.1 =
*Release date: 2024.09.30*

* Fixed duplicate content showing when landing page slider was set to 'header image' due to 'cryout_headerimage_hook' (added in 1.1.3)
* Updated Cryout Framework to 0.8.6.6:
	* Fixed deprecated ${var} usage with PHP 8.2+

= 1.1.3 =
*Release date: 2024.09.12*

* Added 'cryout_headerimage_hook' hook to landing page slider section
* Added additional 'limited' selection for table appearance option for improved compatibility with content plugins
* Enabled more content arrow on mobile devices
* Disabled more content arrow when not needed (like when banner/header image is not fullscreen)
* Fixed XSS vulnerability allowing the output of unsanitized user names set by rogue editors/contributors - reported by stealthcopter on patchstack.com
* Fixed the broken again previously fixed landing page banner image horizontal centering when not fullscreen (since 1.1.0)

= 1.1.2 =
*Release date: 2024.07.13*

* Added 'bravada_navigation_compat' filter to allow overriding the "access" id on menu container and improve uber/mega menu compatibility
* Improved behaviour of site title and logo with custom height sticky menu bar
* Rewrote and fixed the content headings accent effect and also added option to control the effect with the previous homepage-only setting being the default by (un)popular demand.
* Fixed missing YouTube icon in v1.1.1
* Updated to Cryout Framework 0.8.6.5:
	* Updated rich text schema support for comments
	* Precognitively fixed erroneous white square in customize screen panels with Zynith SEO plugin

= 1.1.1 =
*Release date: 2024.01.30*

* Fixed posts navigation being visible on blog (and possibly other sections) due to incomplete conditionality check
* Improved main menu accessibility (tab navigation)
* Fixed theme reset styling overriding block file buttons
* Added new social icons: AliPay, Apple, Behance, Bootstrap, Git, Gitlab, Google, Mastodon, Messenger, Microsoft, Teams, Person (simple, circle, square), QR Code, Rumble, Signal, Snapchat, Sourceforge, Substack, Telegram, Threads, Trello, Unity, Whatsapp, Xbox, and one that shall not be named
* Updated social icons: Twitter (X), Facebook, Github, Google Play, PayPal, Skype, Stripe, Steam, Spotify, Linkedin, Reddit, YouTube, WordPress (old icons are still available by adding the '-old' suffix to the classnames).
* Changed default social icon for tel: links
* Improved theme defaults to make all default configurable texts translatable

= 1.1.0 =
*Release date: 2023.06.26*

* Added interactive hint to WordPress' Homepage Settings panel while using the landing page with a static homepage
* Added support for displaying descriptions as an intro to category sections
* Improved support for bare homepage content by removing the minimum height
* Renamed 'striped' tables option and CSS classname
* Fixed previous/next post navigation images linking to incorrect posts due to discrepancy in same_term parameters
* Fixed empty space after slider image when header image / slider is not set to be displayed fullscreen
* Fixed edit button missing on (static) pages
* Fixed support for longer titles in the title accent position option
* (Hopefully) fixed comments markup inconsistency on WordPress themes demo
* Improved accessibility:
	* Hamburger menu / mobile menu toggler
	* Main menu search
	* Back to top button
	* Loading of the built-in icon font
	* Width and height attributes for portfolio images, featured images and testimonials
* Updated to Cryout Framework 0.8.6.4:
	* Fixed whitespaces in font control title hint due to spaces in markup

= 1.0.8 =
*Release date: 2022.12.30*

* Added generated 'bravada-accent-1/2' and 'bravada-accent-1/2-bg' classnames and 'bravada-accent-1/2' CSS variables for the main accent colors
* Improved styling to support more than two banner/slider caption buttons
* Improved video header centered alignment
* Improved compatibility with ShiftNav plugin by removing focus interception from buttons
* Fixed Google fonts always getting enqueued from remote URL regardless of configured font options
* Fixed page/category titles visibility option not working as expected
* Fixed header overlay appearing on top of the slider caption when slider appearance style is set to 'cryout theme'
* Fixed caption displayed off-screen when slider appearance style is set to 'cryout theme'
* Cleaned up some leftover sidebar layout detection code

= 1.0.7.1 =
*Release date: 2022.05.26*

* Improved Safari mobile browser detection for iPhones and iPads (for better handling of rendering quirks in social apps)
* Improved single posts next/previous navigation by limiting links to same taxonomy
* Updated to Cryout Framework 0.8.6.3:
	* Fixed fatal error on Customize screen due to inconsistent handling of empty categories since WordPress 6.0
	* Fixed 'Disable' and 'All Categories' options not available in category selector options on sites with no categories defined

= 1.0.7 =
*Release date: 2022.04.25*

* Added support for using the associated featured images as header images on WooCommerce's main shop page
* Extended full screen header image option with homepage only setting
* Improved compatibility with script name collision in deferring check by increasing specificity
* Improved compatibility with sub-optimal SSI configurations
* Fixed featured images using the incorrect width in 3 post columns / left sidebar only configuration
* Fixed top navigation always displaying default pages menu
* Fixed main content incorrectly aligned on mobile devices with 3 post columns setting

= 1.0.6.1 =
*Release date: 2021.10.05*

* Fixed a notice displayed in some instances related to the header image since 1.0.6
* Fixed blog homepage sometimes displaying wrong featured image in header since 1.0.6
* Updated to Cryout Framework 0.8.6.2:
	* Added static blog page detection function (for featured images in header)

= 1.0.6 =
*Release date: 2021.09.03*

* Added 'bravda_box_readmore' filter for landing page featured boxes read more texts
* Added support for using the associated featured images as header images on the static home and blog pages
* Renamed Singe Post Titles options to Header Titles for clarity
* Fixed portfolio type lists displaying slugs instead of properly formatted names
* Fixed shortcodes being processed twice on landing page featured boxes read more fields
* Fixed landing page banner image not horizontally centered on very wide screens when not set to be displayed fullscreen
* Fixed header title animation glitch on very specific Safari versions
* Updated to Cryout Framework 0.8.6.1:
	* Added Polylang support for featured boxes category filtering (thanks to espasso)
	* Improved PHP 8.0 compatibility

= 1.0.5 =
*Release date: 2021.04.06*

* Fixed menu in over-image mode overlapping content when header image is not available
* Added configuration hint for header image when the theme's slider / banner image is active on the homepage
* Added visibility control options for byline on single posts and post lists
* Fixed site title accent option not being visible when only site title is displayed
* Fixed 'lighter' font weight typo
* Added ability to hide when navigation area is empty to the main menu toggler
* Added support for anchor (or empty) links in main navigation
* Fine tuned header socials alignment
* Fixed to-top button position when configured to be displayed in the footer and its display/hide animation
* Fixed alignment classes no longer working for some block elements due to their styling removal from WordPress 5.7
* Improved single posts fixed next/previous navigation by moving it to hookable bravada_fixed_nav_links() function and limiting link to same taxonomy

= 1.0.4 =
*Release date: 2021.02.01*

* Removed lazy loading functionality from featured images as it sometimes interferes with image sizes
* Added option to control site title background effect positioning
* Added click-navigation to target panels in header content and site identity hints
* Changed header title animation option to toggle control and renamed/relocated for clarity
* Changed fullscreen header image option to toggle control

= 1.0.3.1 =
*Release date: 2021.01.12*

* Fixed top menu submenus z-index and position
* Fixed socials hover color

= 1.0.3 =
*Release date: 2021.01.06*

* Fixed block editor galleries layout
* Adjusted main menu submenus maximum height
* Fixed landing page arrow JS error when landing page has no content

= 1.0.2.3 =
*Release date: 2021.01.04*

* Fixed back to top button animation when using child themes

= 1.0.2.2 =
*Release date: 2021.01.03*

* Improved preloader handling

= 1.0.2.1 =
*Release date: 2021.01.03*

* Fixed issue when disabling the header title animation

= 1.0.2 =
*Release date: 2020.12.31*

* Added fallback menu to the top navigation area
* Added option to disable animation for lazy loaded images
* Added lazy loading for featured images and single post navigation images
* Optimized frontend.js structure
* Adjusted main menu submenu's dropdown icon alignment
* Fixed header scroll arrow not being clickable; adjusted its focusable areas
* Fixed padding for metas in blog posts
* Removed lazy loading for banner images
* Updated lazy loading for landing page elements to use WordPress functions

= 1.0.1 =
*Release date: 2020.12.29*

* Improved preloader handling when JavaScript is broken on the site or disabled in browser
* Fixed shortcodes over-filtering in some landing page sections
* Fixed images sometimes not appearing due to lazy loading animation
* Fixed header titles support for HTML entities and special characters
* Fixed header video horizontal alignment
* Fixed header titles vertical misalignment on landing page with specific configurations
* Added margins to metas
* Removed hardcoded filter to reactivate WooCommerce's columns count option availability
* Cleaned up and optimized frontend scripts
* Updated theme description
* Updated to Cryout Framework 0.8.5.6:
	* Fixed issues with font families that contain multiple words

= 1.0.0.1 =
*Release date: 2020.12.22*

* Re-upload of 1.0.0 due to missing files

= 1.0.0 =
*Release date: 2020.12.22*

* Fixed interactive widgets not being accessible when used in the header widget area
* Fixed left menu not visible when no widget is present in the left sidebar
* Cleaned up some JS deprecation notices since WordPress 5.6
* Updated to Cryout Framework 0.8.5.5:
	* Fixed Select2 selectors no longer working with WordPress 5.6 on Firefox

= 0.9.3 =
*Release date: 2020.12.14*

* Changed default header content option to title & logo to make logo appear automatically when set without the need of additional configuration steps
* Cleaned up unused commented out code in woocommerce.php
* Removed empty site preview media
* Fixed custom customizer controls type values not being prefixed
* Fixed global JS variables in customizer.js not being prefixed
* Added conditional check and escaping to pingback_url() in header.php
* Improved links accessibility by adding underlining in main content, comments, text widget and landing page text blocks.
* Improved JS code to remove jQuery deprecation notices since WordPress 5.6
* Updated to Cryout Framework 0.8.5.4:
	* Improved JS code to remove jQuery deprecation notices since WordPress 5.6
	* Changed custom post type label in breadcrumbs from singular_name to name
	* Added echo parameters to cryout_schema_microdata() and cryout_font_select() functions

= 0.9.2 =
*Release date: 2020.12.07*

* Added missing bravada.pot file

= 0.9.1 =
*Release date: 2020.12.06*

* Fixed multiple header z-indexes
* Adjusted main menu layout and submenus
* Added extra escaping
* Fixed text indent option appying outside content

= 0.9 =
*Release date: 2020.11.20*

* First Bravada release
