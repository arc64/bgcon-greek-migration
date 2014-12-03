Taxi to Berlin
===================

Berliner Gazette, Berlin, December 2014

Our reportage is currently in english. But in the future...?

[berlinergazette.de/taxi-to-berlin/](berlinergazette.de/taxi-to-berlin/) EN

Licence : GNU General Public License V3

We have forked this project from https://github.com/jplusplus/resonate2014, please go see their project too.


## Installation

### Dependances

	$ sudo apt-get install build-essential python-pip python-dev

and install virtualenv

	$ sudo pip install virtualenv

### Setup a virtualenv and download dependances

	$ make install

### Run the server

	$ make run

### Locales

	$ make update_i18n
	$ make compile_i18n

### Compile the static files

	$ make freeze

### Launch

	$ make run
