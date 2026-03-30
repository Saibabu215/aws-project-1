# aws-project-1
AWS 3-tier architecture project (learning)
# AWS Project 1 - 3 Tier Architecture (In Progress)

## Day 1 - EC2 Setup

- Launched EC2 instance using Amazon Linux 2(project1-server)
- Created key pair for secure login(project1-key.pem)
- Configured security group (allowed SSH - 22, HTTP - 80)(check boxes used)
- Installed Apache web server(sudo yum update -y,sudo yum install httpd -ysudo systemctl start httpdsudo systemctl enable httpd)
- Hosted a simple HTML page(echo "<h1>My AWS Project 1</h1>" | sudo tee /var/www/html/index.html)

## Output
Accessed website using EC2 public IP and verified it is working(echo "<h1>My AWS Project 1</h1>" | sudo tee /var/www/html/index.html)

## Status
Project in progress...
