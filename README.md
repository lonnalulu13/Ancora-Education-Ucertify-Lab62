# Ancora-Education-Ucertify-Lab62
# Managing Software Packages with dpkg


## Objective of the Lab 
In this lab, you will learn to manage software packages with dpkg. Package used dpkg: dpkg is the main package management program in Debian and Debian based System. It is used to install, build, remove, and manage packages.
## Instructions 
### STEP 1 
From the left sidebar, open the Terminal window. 
### STEP 2 
Execute the following command to list all rpm packages:
```bash
dpkg -l
```
### CAUTION 
Press q to quit.
### STEP 3
Execute the following command to list package information for the acl package:
```bash
dpkg -s acl
```
### STEP 4 
Execute the following command to list all of the files that were installed with the acl package:
```bash
dpkg -L acl
```
### STEP 5 
Execute the following command to list the packages that provided the /usr/bin/yes file:
```bash
dpkg -S /usr/bin/yes
```
## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.
