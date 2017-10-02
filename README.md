# Raspcontrol

Raspcontrol is a web control centre written in PHP for Raspberry Pi.

This is a Fork of the orignal Raspcontrol by Bioshox - It appears the repo is no longer available...

***


## Installation

You need a web server installed on your Raspberry Pi.


If you are in a hurry, just clone the repository with:

	git clone https://github.com/wawryk/raspcontrol.git

And create the json authentifation file `/etc/raspcontrol/database.aptmnt` with 740 rights and owned by www-data:

	{
 	   "user":       "yourName",
 	   "password":   "yourPassword"
	}

## Optional configuration

In order to have some beautiful URLs, you can enable URL Rewriting.  
__Note:__ It's not necessary to enable URL Rewriting to use Raspcontrol.



This repo have some fixes with: 
	network statistics, 
	cpu heat - now is in celsius degrees,
	memory statistics.

Test on:
	distribution: Raspbian GNU/Linux 9 (stretch) 
	kernel: Linux 4.9.41+ armv6l 
	firmware: #1023 Tue Aug 8 15:47:12 BST 2017
