These files are the very same ones from
http://googlewebmastercentral.blogspot.co.uk/2011/12/download-search-queries-data-using.html
with some small fixes/improvements.

Also, the only dependecy, gdata, is included as a tar.gz to make it easy to
run these scripts.

Installation
------------

To install using a virtual env you need ``virtualenv`` (package
python-virtualenv in Debian based distros). Once you have that, you just need to
run::

	virtualenv env
	source env/bin/activate
	tar xzf gdata-2.0.18.tar.gz
	cd gdata-2.0.18/
	python setup.py install

Then you need to configure email, password and website from your webmaster-tools
verified account on ``example-create-spreadsheet.py``.
