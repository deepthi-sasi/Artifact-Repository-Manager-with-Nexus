# Demo Project:

## Run Nexus on Droplet and publish artifact to Nexus

Technologies Used:
`Nexus, DigitalOcean, Linux, Java, Gradle, Maven`

Project Description:

## Install and configure Nexus from scratch on a cloud server here Digital Ocean

### Part 1 - Server setup

1. Create Ubuntu Server (Droplet) - min 4GB RAM, 2 CPUs, 160 GB SSD Disk
2. Open SSH port 22
3. Install Java 8
4. Download and Install Nexus
5. Create "nexus" user and group (with 'adduser nexus' command) - Best Practice: Run applications with own user.

###  Part 2 - Configure & access Nexus

1.Make Nexus owner of the folders

   ![nexus folders ownership.png](images/nexus%20folders%20ownership.png)

2.Start with nexus user

   ![nexus start.png](images/nexus%20start.png)

3.Open port 8081 with firewall through DigitalOcean console

4.Access from browser

  ![nexus access.png](images/nexus%20access.png)
  