=== CLI Switch ===
Contributors: kukukuan
Donate link: 
Tags: theme, cli, Command-Line Interface
Requires at least: 2.0.0
Tested up to: 2.1
Stable tag: 1.2

The plugin provides an alternate link ({your-blog-url}/cli) to access your blog with cli theme.

== Description ==

This plugin uses Rod McFarland's [Wordpress CLI theme](http://themes.wordpress.net/columns/1-column/1630/cli-20/ "CLI 2.3 | Theme viewer") as an alternative option without hacking singe line of code.
After the plugin is activated, "{your-blog-url}/{cli-path}" will be directed to the CLI mode. And the CLI theme option will be displayed for configuration even the themes is not activated.
Make sure you have put the  CLI theme files under "wp-content/themes". It works with CLI 2.3 or above.

This plugin is originally modified from [PipperL's plugin -- PL's alternative theme](http://blog.serv.idv.tw/?p=601 "PL's alternative theme (support only CLI 1.0)")
Now it adds support to CLI 2.3. And the support URL is [http://blog.gmap2.net/2007/04/09/wordpress-plugin-cli-switch/](http://blog.gmap2.net/2007/04/09/wordpress-plugin-cli-switch/ "CLI switch support")

== Installation ==

1. Upload `cli-switch.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Configurate the CLI theme through 'CLI Options' section in the 'Theme' menu in WordPress
1. Place a link like "{your-blog-url}/{cli-path}" in your templates (replace {your-blog-url} and {cli-path} with your own blog url)
1. Or you can use function `cli_get_url()` to get the CLI path

== Screenshots ==

== Frequently Asked Questions ==

1. How to use the plugin?
When the plugin is activated, a CLI entry is created. If your blog URL is "http://example.com", the CLI URL is "http://example.com/cli".
You can use this URL to access your wordpress with CLI theme or make a link in your template.