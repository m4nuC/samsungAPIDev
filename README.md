# samsungApi for RepairCMS Development Environment

Vagrant configuration for setting up the development environment for the project

## Instructions:
1. Setup Vagrant on your local computer. Instructions [here](http://docs.vagrantup.com/v2/installation/index.html)
2. Clone this repo somewhere on your computer
3. CD into `samsungAPI/www`
	* execute: `git submodule init`
	* execute: `git submodule update` - Make sure that your public key has been added to authorized user for the main repo ( ask admin )
4. Open your `hosts` file (google if you are unsure how to do that)
	* add `192.168.56.101 samsungAPI.dev`
	* add `192.168.56.101 phpmyadmin`
5. CD back into qcpVagrantDev
	* type `vagrant up` and let the magic happen - THe first time this will take a while depending on connection (5~15 minutes)


Now you should be able to hit [samsungAPI.dev](http://samsungAPI.dev) form your local computer to reach the dev site and [phpmyadmin](http://phpmyadmin) for the PHPMyAdmin GUI

## Trouble shotting:


## Git Workflow:
