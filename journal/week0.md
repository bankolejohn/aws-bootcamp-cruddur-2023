# Week 0 — Billing and Architecture

## I was able to create a napkin for the Cruddur app. 
## Here is the link https://lucid.app/lucidchart/be9be196-1ae3-4ed4-9785-8b8a01241b41/edit?viewport_loc=-11%2C-84%2C1480%2C636%2C0_0&invitationId=inv_e558483d-196b-4930-bf8a-bc351b84c344

![Screenshot 2023-02-19 154602](https://user-images.githubusercontent.com/76499525/219990622-c5bc7712-13c8-4490-86a1-c27cac117b11.png)

## AWS CLI installed on gitpod successfully using the code below: 
##  curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install

## AWS CLI was also installed on my local machine successfully via the steps below:
Download and run the AWS CLI MSI installer for Windows (64-bit):

https://awscli.amazonaws.com/AWSCLIV2.msi
Alternatively, you can run the msiexec command to run the MSI installer.

msiexec.exe /i https://awscli.amazonaws.com/AWSCLIV2.msi

To confirm the installation, open the Start menu, search for cmd to open a command prompt window, and at the command prompt use the aws --version command. 

aws --version

![Screenshot 2023-02-25 033341](https://user-images.githubusercontent.com/76499525/221332030-4027ddb3-faa2-4ae5-b649-e41d7f16c6b0.png)


I entered the commmand: **aws sts get-caller-identity**

![Screenshot 2023-02-25 034336](https://user-images.githubusercontent.com/76499525/221332263-ebc98409-d238-40b3-879b-55c5739041db.png)

**Note that the account id here is not what I am using for the bootcamp. I had earlier configured this CLI to use a different account**

### i created a logical diagram for the cruddur app using lucid chart

https://lucid.app/lucidchart/286406e3-afa3-40b8-aec2-12522a66780e/edit?viewport_loc=74%2C156%2C2184%2C954%2C0_0&invitationId=inv_a8adde70-1c0b-41a6-8e37-11125ac13ec6

### challenges when creating the logical diagram

I wasn't able to create the momento logo

### Create a billing alarm

### Create a budget 
