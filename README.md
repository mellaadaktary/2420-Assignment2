# Assignment 2: Shell Scripting

This Assignment consists of two main scripts, System Setup Scripts and User Creation script.
Each script contains multiple part to it which ultimately automate the process. 
## Part 1: Configuration Scripts
the point of these Configuration Scripts are to automate the set up of a new system which can be very time consuming. These Scripts two main problems, 1. installing packages and 2. copying configuration files into different locations to make the software to your liking. That is what this script is going to solve.

##### The configuration scrips include the following components:
1. A file which contains user-defined list of packages to be installed
2. A script to install those packages
3. Existing configuration files for several applications on a repository to be cloned and the script to make symbolic links from those configuration files
5. A script to call the other scripts

## Part 2: New User Script
The purpose of this script is to create a new user without the assitance of any existing built in tools

##### The new user script includes the following components:
A specified shell
A home directory created
the contents of the .etc.skel directory copied into the home directory
Additional groups that could be added(new user should have a primary group that matches their username)
password created using the passwd utility