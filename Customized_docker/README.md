This contains the modifed docker files to run the default original template of the conpot honeypot

# Original from mushorg

* Original means that the templates are not modified except that the ports are changed to standard ports using the authbind

* purpose is to see if shodan.io can find out that this is honeypot and not the other one customized by us

# First obs from nmap: 

* somehow the customized and original open same ports even if we did not expose port 44818 in docker-compose

* seems like in defualt template these are standard ports exposed , need to check the code
