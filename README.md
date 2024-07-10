# Overview
  1. This project deals with deployment of a 2 tier Flask Application to Elastic Kubernestes Services(EKS)
  2. 𝗖𝗼𝗻𝘁𝗮𝗻𝗿𝗶𝘀𝗮𝘁𝗶𝗼𝗻 is done with the help of 𝗱𝗼𝗰𝗸𝗲𝗿
  3. Frontend and backend(db) images are stored in dockerhub
  4. yml menifest has been created and also config map  and secrets are used
  5. Kubernetes cluster in EKS is created with the help of EKSCTL command
     
     `eksctl create cluster --name eks_cluster --region us-east-1 --fargate`

  6. for deployment to cluster following command is used

     `kubectl apply -f deployment.yml`
     
     
  
# Technologies 
- Flask
- Docker
- kubernetes
- EKS
- Heml
- AWS
