# Assignment 2: Shell Scripting

This Assignment consists of two main scripts, System Setup Scripts and User Creation script.

## Part 1: Configuration Scripts
the point of these Configuration Scripts are to automate the set up of a new system which can be very time consuming. These Scripts two main problems, 1. installing packages and 2. copying configuration files into different locations to make the software to your liking

##### The configuration scrips include the following components:
A user-defined list of packages to be installed
A script to install those packages
Existing configuration files for several applications
A script to make symbolic links from those configuration files
A script to call the other scripts

## Part 2: New User Script
The purpose of this script is to create a new user without the assitance of any existing built in tools

##### The new user script includes the following components:
A specified shell
A home directory created
the contents of the .etc.skel directory copied into the home directory
Additional groups that could be added(new user should have a primary group that matches their username)
password created using the passwd utility