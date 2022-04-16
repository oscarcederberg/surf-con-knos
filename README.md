# surf con knos
surf is a simple Web browser based on WebKit/GTK+. This contains patches that I've added from suckless.org.

## Installation
```
sudo make clean install
```

## Running surf
```
surf [URI]
```
See the manpage for further options.

## Running surf in tabbed
For running surf in tabbed[1] there is a script included in the distribution,
which is run like this:

	surf-open.sh [URI]

Further invocations of the script will run surf with the specified URI in this
instance of tabbed.

[0] http://tools.suckless.org/dmenu
[1] http://tools.suckless.org/tabbed
