# Manage JSS

## Function
Allows easy starting, stopping, and restarting of the Jamf Pro Tomcat process.

#### Optional
`systemd_JSS.yml` installs `jamfpro.service`, a native systemd service.  The primary driver for this was automatic restarts, should the service halt or crash.  *If you choose to use it, be sure to modify the Environment variables as needed.*

## Tested Environment(s)
RHEL 7 & CentOS 7

## Changelog

**v1.1 (2017-08-07)**
* Added systemd_JSS.yml and files/jamfpro.service

**v1.0 (2016-09-01)**
* Original Release
