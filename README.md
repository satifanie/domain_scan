domain_scan
===========

a scripts to detect available domain for registering by using envoy, whois and python


You should have installed envoy and pyparsing,if not,you can install them by using following command:


pyparsing:

easy_install pyparsing


envoy:

https://github.com/kennethreitz/envoy

git clone https://github.com/kennethreitz/envoy.git

cd envoy

python setup.py install


Usage:

Run a command, get the available domain to register

examples:

python av-domain-scan.py ??42.com

note: wildcard '?' represent all string according with regex expression r'[0-9a-zA-Z]'

if all domains had been registered, script will print nothing, otherwise print available domains.

