# Materials for the March 2017 meeting of Women Who Code Belfast

## Overview

This repository contains a single IntelliJ project, designed to run in IntelliJ Community Edition with the 
Scala plug-in and SDK installed.

The steps to get everything up and running are as follows:
1. If you don't have JDK 8 installed on your machine then do that first.
2. Download the Community edition of IntelliJ from [here](https://www.jetbrains.com/idea/#chooseYourEdition)
3. Run the installer. The final screen of the wizard will invite you to install the Scala plug-in, choose to do so.
4. Run IntelliJ and open the project.
5. Right-click on the project and open the 'Module Settings' 
6. On the 'Dependencies' tab you will need to:
  * Specify a Java SDK which is present on your machine
  * Delete the specified Scala SDK and install one of your own (via the green plus)
7. On the 'Sources' tab make sure the version of Java is set to '1.8'
8. You should now be able to build the project and run the 'Program' class in the package 'learning.fp.scala.demos'

    
