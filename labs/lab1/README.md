# Lab 1: Install OneAgent on your production & test hosts with appropriate host groups

In this lab, we will install the Dynatrace OneAgent in the Production and Staging environments using the MSI installer

## Instructions

1. Use the provided credentials to log in to your **Production** server.
2. Login to your Dynatrace environment using the credentials provided.
3. Download OneAgent MSI installer.

![Download OneAgent for Windows](/assets/oneagent-msi-installer.png)

4. Modify the Exercise 1 – AgentInstall.bat file (found on the desktop) with the appropriate information. The appropriate info can be found in the intall.bat file contained in the MSI package.

You need to collect **token** & **token** from the install.bat and populate in the Exercise 1 – AgentInstall.bat file

Also, you'll need to change the file name referenced to the version of the MSI you have downloaded.

Copy the OneAgent MSI file to C:\

![Modify the Exercise 1 – AgentInstall.bat file](/assets/install-batfile.png)

5. Run the Exercise 1 – AgentInstall.bat file

Right click on the Exercise1 – AgentInstall.bat file, select Run as administrator

![AgentInstall.bat file - Run as Administrator](/assets/run-as-administrator.png)

6. Start Easy Travel - UEM - Standard senario

7. Check Host appears in Dynatrace and has the appropriate HostGroup assigned.
8. Repeat above instructions for Staging server. 

Please ensure you set the hostgroup to Staging for the Staging server.

:arrow_up: [Back to TOC](/README.md)
