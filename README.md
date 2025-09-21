# Class7HW-Week1
Lab Work Instructions:

Security Groups

	Sign into AWS Console
	Search Bar "EC2"
	Menu on left of screen
	Scroll down to Network & Security
	Select: "Security Groups"
	Create New Security group
	Name it with no space "Class7Sep2025"
	Description gets same name
	Vpc default
	Inbound Rules
	Add Rule
	HTTP
	Source Type "Anywhere-ipv4"
	Description (optional) "my homepage"
	AVOID OUTBOUND RULES AT ALL COSTS
	Tags: optional
	Value: same name as Security Group
	Create Security Group
EC2
	Instances: Launch Instance
	Name Tags: instance name same
	Keep Amazon Linux and other defaults DNT!
	Instance Type default t.3xxx or t.2xxx
	
	Key Pair: proceed w/o keypair
	Network Settings: Defaults
	Select: select existing security group
	Common security group: Select newly made group
	Advanced Details: Scroll down to bottom User Data
		Go to Github Repo: https://github.com/MookieWAF/bmc4/blob/main/ec2scrpit
		Copy script
	Go back to Advance Details
	Paste Script
	Launch Instance
	Click link of successful instance
	 Instance Summary
	Copy Public DNS
Open new tab http://"pastelink"
http://ec2-54-226-234-62.compute-1.amazonaws.com

From <https://us-east-1.console.aws.amazon.com/ec2/home?region=us-east-1> <img width="733" height="1004" alt="image" src="https://github.com/user-attachments/assets/74f64f38-530d-4bff-98d2-f3aac7bbaeac" />
<img width="525" height="543" alt="image" src="https://github.com/user-attachments/assets/e8cf2d66-7482-4484-9059-3cadfc1c0eeb" />
Go instances
select instant state dropdown
Terminate/Delete selected instance
