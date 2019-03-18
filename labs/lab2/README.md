# Lab 2: Create automatic tagging rules

In this lab, we will create automatic tagging rules to tag  Staging and Production environments based on the Host Groups.

## Instructions

1. Access Automatic tagging rules, select **Settings -> Tags -> Automatically applied tags**

2. Add new tagging rule for **production**

## Name: Production

Rule applied to Services.

Rule applies to entities matching Host Group : **Production**

Have it apply to underlying hosts of matching services.

Have it apply to underlying process groups of matching services.

![HostGroup Auto Tagging](/assets/hostgroup-autotag.PNG)


3. Add new tagging rule **staging**

## Name: Staging

Rule applied to Services.

Rule applies to entities matching Host Group : **Staging**

Have it apply to underlying hosts of matching services.

Have it apply to underlying process groups of matching services.

![HostGroup Auto Tagging](/assets/hostgroup-autotag-staging.PNG)


:arrow_up: [Back to TOC](/README.md)
