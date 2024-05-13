# EKS
steps to create EKS

    1.Create system level user to access aws account
    2.Overall eks setup :
        Provision an EKS cluster --> Deploy worker nodes --> Connect to EKS --> Run/Deploy Kubernetes app
Step 1

    1.(a) Provision an EKS cluster
        :-Create IAM role, refer : https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/eks_cluster
       :- Get VPC details
       :- Create EKS cluster
step 2

    2.(a) Deploy worker node
            https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/eks_node_group
        :-Create IAM role
        Create node groupe