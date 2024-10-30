=== Plugin Name ===
Contributors: daanzk
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=TL4JJ3KHQCC6A&lc=NL&currency_code=EUR
Tags: meteohub, meteo, shorttags
Requires at least: 3.0.1
Tested up to: 6.4.2
Stable tag: 1.3.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin lets you show the data from Meteohub all-sensors.txt file easily in the content of your website using shorttags.

== Description ==

This plugin lets you show the data from Meteohub all-sensors.txt file easily in the content of your website using shorttags.

For example:<br>
`Temperature: [meteohub sensor='actual_th1_temp_c']&deg;C<br>
Max windspeed: [meteohub sensor='alltime_wind0_maxspeeddir_nl'] [meteohub sensor='alltime_wind0_gustspeedmax_bft'] bft ([meteohub sensor='alltime_wind0_gustspeedmax_kmh']) on [meteohub sensor='alltime_wind0_gustspeedmax_time']
<br><br>
will result in:
<br><br>
Temperature: 9&deg;C<br>
Max windspeed: NNW 12.4 bft (130.3 km/h) on 28-10-2013 at 12:31<br>`

The plugin automatically rewrites the date and time according to your WordPress time and date settings, and trend values get rewritten to arrow images.

I am in no way, shape or form affiliated with Meteohub and do not in any way profit from commissions or referrals to them.

== Installation ==

1. Upload `meteohub.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Navigate to the plugin settings and enter the meteohub all-sensors.txt file path or URL.

== Screenshots ==

1. The settings.
2. The usage.
3. The output.

== Changelog ==
= 1.3.1
* Updated supported Wordpress version

= 1.3 =
* Updated supported Wordpress version

= 1.2 =
* Fixed a bug displaying the trend arrows incorrectly.
* Fixed a bug displaying date/time wrong.

= 1.1 =
* Added backward compatibility with the old Meteodata plugin. The meteodata tag is now treated like the meteohub tag.

= 1.0 =
* Initial release.
