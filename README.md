The database footprintDB has a Web interface at http://floresta.eead.csic.es/footprintdb

It has been described at:
* https://doi.org/10.1093/bioinformatics/btt663
* https://link.springer.com/protocol/10.1007%2F978-1-4939-6396-6_17

The script [footprintDBclient.pl](./footprintDBclient.pl) is for users that wish to query footprintDB from the command-line through the Web Services interface.

# Dependencies 

It uses Perl module SOAP::Lite, at https://metacpan.org/pod/SOAP::Lite, which can be 
installed with 

	sudo cpan -i SOAP::Lite

