# panel_ticker
Single-line, API-powered stock ticker intended for use with GNOME Shell and the Executor shell extension.

![screenshot](screenshot.png?raw=true "Screenshot")

# Instructions for intended application

Install Executor (https://extensions.gnome.org/extension/2932/executor/) and configure it to run panel_ticker every second.

Multiple ticker symbols may be supplied to panel_ticker as arguments:
* `path/to/panel_ticker aapl amzn`
One will be displayed at a time for the duration defined by SECONDS_PER_SYMBOL.

![screenshot_config](screenshot_config.png?raw=true "Screenshot of config")
