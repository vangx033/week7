
#!/bin/bash
#Xee Ho Vang
# week7 - Chapter 7 script

# Testing the system logger
logger -p daemon.info Hey this is testing

# Showing terminals and display a login prompt
ps ao args | grep getty

# Checking password-setting parameter
grep password.*unix /etc/pam.d*

echo "Thanks for looking"
