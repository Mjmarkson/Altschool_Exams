##Steps I took in achieving my exams

#Steps in provisioning a server in AWS EC2

1.	Logged into my AWS account
2.	In the AWS management console select EC2 and click Launch Instance 
3.	Configure instance starting from Name: “mfoniso-markson_AltSchool”
4.	Amazon Machine Image (AMI):  Ubuntu Server 22.04 LTS
5.	Instance Type: t2.micro (Free Tier eligible)
6.	Key Pair: Click "Create new key pair", choose .pem format → download and save
7.	Network Settings:  Allow HTTP (port 80) — for web server and HTTPS (port 443) — for secure traffic (optional, for SSL)
8.	Storage-- (8 GB) for basic usage 
9.	Launch Instance
#Steps in connect local server via terminal to Aws instance
10.	Used Terminal on my local machine to connect to my Instance using my ip address
11.	Used the Chmod command to allow permission to connect my instance to the “Key pair”, then I SSH into the instance using the IP shown on the Ec2 dashboard
12.	Installed Nginx using the “sudo apt install -y” command 
13.	For the front end, created a landing page using Vscode as my code editor using both HTML and CSS then wrote a dynamic script showing “greetings” and “time”
14.	Pushed my web page from my local machine to my Aws instance using my key and IP address all from my AWS instance
15.	Moved my files to Nginx root 
16.	Tested my http://34.244.133.195  to confirm site was hosted 
![image](https://github.com/user-attachments/assets/23e1688a-5502-476b-8e86-ff2b0bfc9580)
