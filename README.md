# panel_ticker
Stock ticker intended for use with GNOME 3 and the Executor plugin, though other single-line output script repeaters may exist and could be compatible.

# Intended instructions:

Install Executor (https://extensions.gnome.org/extension/2932/executor/) and configure it to run panel_ticker every second.

Any single ticker symbol may be supplied to panel_ticker as an argument. Example: `$ path/to/panel_ticker aapl`

For certain ambiguous symbols, providing the nasdaq: tag will cause Google to return stock information more reliably: `$ path/to/panel_ticker nasdaq:ford`
