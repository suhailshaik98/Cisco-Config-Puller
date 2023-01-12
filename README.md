# Cisco-Config-Puller
This is the code which provides an interface to easily pull the configuration of a Cisco switch or router through telnet saves it in a text file

## Why is this useful?
When writing configurations, many network engineers will always keep a backup of these configurations. However, in a live environment, there are many switches, and getting configurations from all these switches can be pretty exhausting. This is because he/she will have to deal with the following problems:

•	Logging in with the same username and password at every switch

•	The network engineer will have to use the console screen to copy by manually dragging the cursor (There could be more than 100 lines of configuration code in some cases), copying it for every switch and router, and pasting it into a text file.

### How does this program solve the problem?
This program provides a Graphical User Interface (GUI) for the network engineer, where he/she would have to enter the following details such as:

•	Username

•	Password (enable and local)

•	IP Address of the Switch

•	File name for the text file.

This allows for quickly editing the IP address in the GUI while other user input blanks remain the same.

## Can it be used for any router or switch?
It has been tested only for a single cisco switch, but it is assumed it will work for most cisco network products with telnet access.

## What are the drawbacks?
•	Incompatibility with other brands of network devices

•	It does not provide any feedback if the file had been successfully created or not

•	Improvement can be made in providing more output about the process that is being done

•	The network engineer/ technician will need telnet access and this does not work with a console port.

The exe file is provided here 

https://github.com/suhailshaik98/Cisco-Config-Puller/blob/main/CiscoShowConfig/test.exe

The test output has been provided here

https://github.com/suhailshaik98/Cisco-Config-Puller/blob/main/CiscoShowConfig/suhail.txt
