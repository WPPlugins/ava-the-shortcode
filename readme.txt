=== Ava The Shortcode ===
Contributors: wilcosky
Tags: shortcode, shortcodes, avatar, user, ava
Requires at least: 4.6
Tested up to: 4.8
Stable tag: 1.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Show the current user's avatar anywhere. Or, any user avatar for that matter. Is that it? Yes. Don't sass me. 

== Description ==

Using the simple shortcode [ava] you can make the current logged in user's avatar appear. Use it anywhere shortcodes are allowed. 

If you want to show a different user's avatar, find out what their user id is. Then include it in the shortcode like this:

[ava id="1"]

"But, I want to put it in a php file where shortcodes don't work!" Fine! Just use:

echo do_shortcode( '[ava]' );

"But, I want it to be smaller or bigger!" Now you're pushing your luck. But, whatever. Just do this:

[ava size="32"] or [ava id="1" size="32" alt="me"]

"But, I want..." SHH! Go meditate. Calm down. Use a different plugin if you want more. 

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/ava` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Place [ava] in a page. 
4. Use CSS to make it pretty. 


== Frequently Asked Questions ==

= How do I style the avatar? =

With CSS.

= Okay. Could you be a little more specific? =

Try this first: [ava class="whatever"]

Then, put the following code where your custom CSS is:

.whatever{border-radius:50%; width:50%;}

Now, if that does not work, I recommend wrapping the shortcode in a span tag with a class. For example: `<span class="whatever">`[ava]`</span>`

Either way, you need to know some CSS/HTML basics. Google how to style the Wordpress avatar. One day I may beef this plugin up and provide more instructions. But, for now, Ava is who she is. Simple. But, lovely.

== Changelog ==

= 1.0 =
* The release.

== Upgrade Notice ==

= 1.0 =
No upgrades yet.