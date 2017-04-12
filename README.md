# Packer.io-CKAN
This is a Packer.io build of a CKAN server running on Ubuntu14.04

Althought the Packer.io doco makes it look all very simple, the devil is in the detail. The preseed.cfg file seems to break easily and has trouble with getting through the Ubuntu install interactions properly for a Desktop install. Ubuntu server would be easier but is less useful for dev/test purposes. In the preseed.cfg files "di" stands for Debian Install and they have to be matched to the exact version of Ubuntu.
