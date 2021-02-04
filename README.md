# linux-login
### create a ec2 aws instance
### at this time u will get a .pem file
### check summery and connect summery to get the IP address
### download putty in your machine
### search puttyGen and click on load select your .pem file and select save private file(called as ppe file)
### now open putty andin session put the ip address(host name)
### click on ssh->auth select the private file to import.
### if u want to save the session u can save there.
### a linux window will be opened
### enter the user name there ec2-user
### yaa..u loged in

# if u have the .pem file only
### goto to the .pem file location
### open git bash
###  ssh -i "sarita_linux_key.pem" ec2-user@ec2-35-173-133-75.compute-1.amazonaws.c
### -i means instance
### sarita_linux_key.pem is the user name
### then @ ec2-35-173-133-75.compute-1.amazonaws.c is the ip address
