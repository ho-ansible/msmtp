# Ansible role: msmtp
Forwarding-only local MTA

## Requirements
Only tested on Debian stable, for now.

## Role Variables
+ `msmtp_host` (default: smtp.gmail.com): upstream server
+ `msmtp_login`: auth to upstream
+ `msmtp_pw`: auth to upstream
+ `msmtp_recipient` (default: same as `msmtp_login`): sending address

## Dependencies
None.

## License
MIT

## Author Information
Sean Ho, https://github.com/ho-ansible/
