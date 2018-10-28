**** Fail2ban Service ***** 


fail2ban.yaml


THis playbook installs and configures Fail2ban Service on Amazon-Linux and CentOS7 

The requirement to install Fail2ban service is epel-release repository
1. It installs epel-release on CentOS7
2. It installs epel-release on Amazon-Linux
3. Installs Fail2ban service on Amazon-Linux and CentOS7
4. Enables Fail2ban Service 
5. Creates configuration file on CentOS7
6. Configures Fail2ban service on CentOS7
7. Configures Fail2ban service on Amazon-Linux
8. Restarts Fail2ban service on Amazon-Linux
9. Restarts Fail2ban service on CentOS7 

** Fail2ban Configuration"

The configuration:
1. Allows 3 retry
2. Allows 2 minutes to login
3. If failed to login, bans for 1 hour
4. Ignores company's CIDR block

