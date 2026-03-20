###Demo Project:

###Run Nexus on Droplet and publish artifact to Nexus

Technologies Used:
`Nexus, DigitalOcean, Linux, Java, Gradle, Maven`

Project Description:

##Install and configure Nexus from scratch on a clous server here Digital Ocean`

##Summary of the steps:

Create Ubuntu Server (Droplet) - min 4GB RAM, 2 CPUs, 160 GB SSD Disk
1.Open SSH port 22

2.Install Java 8

3.Download and Install Nexus

4.Create "nexus" user and group (with 'adduser nexus' command) - Best Practice: Run applications with own user.

##Install and Run Nexus on a Cloud Server - Part 2

1.Make Nexus owner of the folders

   ![nexus folders ownership.png](images/nexus%20folders%20ownership.png)

2.Start with nexus user

   ![nexus start.png](images/nexus%20start.png)

3.Open port 8081 with firewall through DigitalOcean console

4.Access from browser

  ![nexus access.png](images/nexus%20access.png)
  