# Nginx Reverse Proxy Task

## Intro
The focus of this task was to change the code in the Vagrant file so that the app would be running on port 80 instead of port 3000 i.e. setting up a proxy.
The task requirements can be found under [Proxy Task DOD](https://github.com/MattSokol79/App_MVM_Reverse_Proxy/tree/main/Proxy%20Task%20DOD) 

## Pre-requisites
- Install Vagrant
- Install VirtualBox
- Install Ruby

## Instructions
To work in this box:
1. Clone repo/copy files into your code editor
2. In commandline/bash make sure youre in the folder containing Vagrantfile and run:
```bash
vagrant up
```

Now the app is running on:
- ip: 192.168.10.100

Db running on:
- ip: 192.168.10.200

**To see website working**
The website will now be running on:
- 192.168.10.100
- 192.168.10.100/fibonacci/{index}
- 192.168.10.100/posts

Testing CI and Jenkins Try again and try the tests, try tests again (3)