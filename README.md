# pia
Linux script to connect to privateinternetaccess VPN, forward ports and lock down firewall

# Usage:
	Usage: ./pia [Options]
		-u	- Update PIA openvpn files.
		-p	- Forward a port.
		-h	- This help.

# Dependancies:
	openvpn
	ufw
	bind9

On initial running of the script a check for these is made and if not found, they are intalled using APT


Tested working on Debian Wheezy and Kali Linux