# ACIT 2420 Assignment 2

## Table of Contents

- [VPC Setup](#vpc-setup)

## VPC Setup

1. On DigitalOcean, click on "Networking" then "VPC" then "Create VPC Network".

2. Set the preferred data centre.

3. Set the IP range to be generated by DigitalOcean.

4. Set the name of the VPC to something you can remember.

5. If the VPC was created successfully, you should be able to see the VPC under the "VPC" tab after clicking on "Networking".

![viewing created VPC](images/ss1.png)

## Creating Droplets

- Note: Before beginning, you will need to have a custom SSH key generated and added to DigitalOcean.

1. Create a new Droplet on DigitalOcean

- Note: All the settings will be set to default if not specified in the instructions below.

2. Set the VPC network to the VPC network you had just created.

![droplet vpc setting](images/ss2.png)

3. CPU option can be set to anything. I will be using the cheapest option.

4. Set the SSH key a key that is added to DigitalOcean.

5. Set the number of droplets to 2.

6. Set the name of one droplet to "server-one".

7. Set the name of the other droplet to "server-two".

8. Add the tag "Web".

9. Click on "Create Droplet".

If done successfully, 2 droplets should have been generated with the tag "Web" and its names set to "server-one" and "server-two"

![generated droplets](images/ss3.png)










