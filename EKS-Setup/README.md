AWS EKS cluster setup

1 - Cover prerequisites
2 - Create base AWS infrastructure
3 - create K8s control plane
4 - Install & configure kubectl
5 - launch the K8s EC2 worker nodes

# Princing

> $ 0.20/h
> $ 144/m

# Cover prerequisites
- Create IAM role
K8s assumes this role to create AWS resources

- Create ssh key
to be able to ssh to your EC2 instances

- Create Access key+secret
enables authentication for API access

# Create base AWS infrastructure
- Create VPC multi-AZ
- Create Security group