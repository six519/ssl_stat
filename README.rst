ssl_stat
========

Python C Language Extension To Get SSL Certificate Information 

Install Dependency (Ubuntu)
===========================
::

    apt install libcurl4-openssl-dev

Building and Installing
=======================
::

	./setup.py build install

Installing Through PyPi
=======================
::

	pip install ssl_stat

Python Sample Usage
===================
::

	import ssl_stat
	ssl_stat.check("https://example.com")