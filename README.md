# Load Balancer DNS Name
http://dtq-ud-loadb-wtzmbyird4ru-444491379.us-east-1.elb.amazonaws.com

# infrastructure diagram
Refer to file: project3_infrastructure_diagram.PNG

# Script for create, update, delete stack

## Create stack sample:
./create.sh dtq-udagram-instance udagram.yml udagram-parameters.json

## Delete stack sample:
./delete.sh dtq-udagram-instance

## Update stack sample:
./update.sh dtq-udagram-instance udagram.yml udagram-parameters.json