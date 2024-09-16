# vpc-basic
create a basic vpc with 2 available zones 

command to create a instance t2.micro from CLI.

aws ec2 run-instances --image-id {AMI_ID} --instance-type t2.micro --security-group-ids {SECURITY_GROUP_ID} --subnet-id {SUBNET_ID} --key-name {KEY_PAIR_NAME} --user-data file://{NAME_SCRIPT_TO_GET_METADATA} --metadata-options HttpTokens=optional
