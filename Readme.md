#### Cloud monitering app

##### 1. Devlopment :

- Build and Push the code to the repo that u created "`python3 ecr.py`" . But must have boto3 and aws configured in the system .

##### 2. Deployment :

- Create a eks cluster on aws consol then fetch the config. and then configure the deployment , service . For external access use a ingress controller or any other aws lb to redirect the traffic to the node port .` python3 eks.py`
