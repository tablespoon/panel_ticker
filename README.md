# panel_ticker
Stock ticker intended for use with GNOME 3 and the Executor plugin, though other single-line output script repeaters may exist and could be compatible.

![screenshot](screenshot.png?raw=true "Screenshot")

# Intended instructions:

Install Executor (https://extensions.gnome.org/extension/2932/executor/) and configure it to run panel_ticker every second.

Any single ticker symbol may be supplied to panel_ticker as an argument:
* `path/to/panel_ticker aapl`

For certain ambiguous symbols, providing the `nasdaq:` tag will encourage Google to return stock information more reliably:
* `path/to/panel_ticker nasdaq:ford`

![screenshot_config](screenshot_config.png?raw=true "Screenshot of config")

Since open APIs have become scarce, this functions by scraping Google. In order to be courteous (and to avoid getting blocked), the script is configured to query no more than once every 180 seconds.
