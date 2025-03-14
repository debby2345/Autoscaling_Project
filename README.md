# Autoscaling_Project
 This project document the process of Creating an Autoscaling Group
### Auto Scaling Group Creation
Named the Auto Scaling group and Selected a launch template, 
Below is the image
![Autoscaling Creation](/launch_template.PNG)

Configured instance launch options by selecting a key pair and Amazon Machine Image (AMI), and utilized the default VPC.
![keypair and AMI](/key_and_AMI.PNG)

### Network Settings and Integration Configuration
Choose three availability zones and subnets, and selected a balanced best effort.
![Network](/network_setting.PNG)
![Integration](/integration.PNG)

### Health Check Configuration
Configured the health check with a 300-second grace period
![HEALTH Check](/health_check.PNG)

### Group sizing and Scaling 
set the desired capacity to 1, Minimum desired capacity to 1, and Maximum desired capacity to 2. No scaling policy was implemented.
![group sizing](/group_sizing.PNG)

### Autoscaling Group Successfully Created
Successfully created the Autoscaling Group.
![Autoscaling](/asg_successful.PNG)
![Autoscaling](/autoscaling_instance.PNG)

