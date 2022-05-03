# Zero Passwords Server

## Oct 2013 – Sep 2019

### Project Description

Problem: I want to setup Ubuntu servers without having to type a password each time a script needs admin rights.

Solution: Using the pam_ssh_agent_auth module, derived from OpenSSH by Jamie Beverly and other contributors, I can run sudo commands on the server authenticated through SSH alone, without a password. I have developed shell scripts that automate this setup, starting from a freshly created Ubuntu server.

### See project

* [Zero Passwords Server](https://github.com/eric-brechemier/zero-passwords-server)
