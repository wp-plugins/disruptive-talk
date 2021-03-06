=== Disruptive Talk ===
Contributors: disruptive.io, michaelmackus
Donate link: http://disruptive.io/
Tags: widget, plugin, social, audio, free, phono, tropo
Requires at least: 3.0.x
Tested up to: 3.2.3
Stable tag: 1.4.1

Disruptive talk phono widget. Use phono to allow your wordpress users to call a phone 
	number right from your site, for free!

== Description ==

Disruptive talk phono widget. Use phono to allow your wordpress users to call a 
	phone number right from your site, for free!

Optionally supports "proactive calls". After a defined amount of seconds, the widget 
	will pop up as a jquery modal popup.

The phono widget can call any landline phone number, sip address, or Tropo application.
	Register your app at Tropo.com for extended functionality. 

For more information check out 
	http://disruptive.io/disruptivetalk-proactive-phono-wordpress-plugin-for-tropo/

== Installation ==

1. Download the Plugin
2. Install the Plugin by copying it to your wp-content/plugins directory
3. Using the Plugins page in the WordPress Admin Area activate the plugin
4. Configure the Plugin by going to Settings -> Disruptive Talk
5. Add the widget to the page you want it to show up on by going to 
	Appearance -> Widgets and dragging the Widget to the sidebar or footer area 
	where you want it to show up at.
6. Add the following code to your theme's header.php file: (Internet Explorer fix)
	<meta http-equiv="x-ua-compatible" content="IE=8">

Detailed installation instructions at
	http://disruptive.io/disruptivetalk-download-and-installation/

== Frequently Asked Questions ==

= Does the browser phone require flash? =

The browser phone does require flash to use your computer's mic. We are working
	on a version with a "call me back" option, so users without flash (for instance
	users on an iPhone or Android device) will still be able to use the phone.

== Screenshots ==

1. Disruptive Talk proactive widget.
2. Disruptive Talk proactive widget - in a call.
3. Disruptive Talk embedded widget.

== Changelog ==

= 1.4.1 =
* Bug in IE in some themes. You must now manually add the meta tag to your theme's header.php file.
* Detects if a user is on a mobile device. If so, the plugin displays the phone number instead of the phono widget. In a future version, we are planning mobile callback.

= 1.4 =
* Fixed bug in IE (again). Seems like Phono requires IE 8 standards mode.

= 1.3 =
* Fixed path bug - Widget was broken on most sites due to path differences.

= 1.1 =
* Fixed bug in IE.

= 1.0 =
* Initial commit.

== Upgrade Notice ==

= 1.4.1 =
* Add the following code to your theme's header.php file: (Internet Explorer fix)
	<meta http-equiv="x-ua-compatible" content="IE=8">

= 1.4 =
* Fixed bug in IE. The plugin now forces your theme into IE 8 standards 
	mode so the phono widget can work properly.

= 1.0 =
* Initial commit.
