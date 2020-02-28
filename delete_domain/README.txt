INTRODUCTION:
------------

This module contains script files to  delete domains.


REQUIREMENTS:
------------

This module requires the following modules:

 * Python 3
   Libraries
  * requests
  * sys
  * json
  * time

 * The scripts must be run outside sddc-manager environment.

 * DNS resolution must be done for sddc-manager.


PREREQUSITES:
--------------

The following data is required

ID of the domain that has to be deleted.

TIP
Back up the data on the domain.
TIP
Migrate the VMs that you want to retain, to another domain.



USAGE:
-----

Usage:	python delete_domain.py <hostname> <username> <password> <domain_id>

