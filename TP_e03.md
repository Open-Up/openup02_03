# TP LDAP

In this practical work (1h30), you will install, configure and provide data to a LDAP server. You will then use it for Linux authentication.

## Q 1 : Install OpenLDAP

 - Boot 1 virtual machine, name it LDAP server
 - Install slapd on it. Note the admin password used.
 - remove /etc/ldap/slapd.d
 - Provide a working configuration and start it

## Q 2 : Feed it with users

 - Write a LDIF file containing 5 users (Your domain name is openup.com, your organization bachkhoa)
 - add it to the LDAP server

## Q 3 : Search a LDAP

 - Provide the query to find :
    - All users
    - The user with a given address

## Q 4 : ACL management

 - Passwords should not be shown
 - Authentication should be possible

## Q 5 : PAM

 - Add a network interface for both server and client in a private network.
 - Configure it to use a private IP in /etc/network/interfaces
 - Configure the client to use the LDAP server for authentication : https://wiki.debian.org/LDAP/PAM

