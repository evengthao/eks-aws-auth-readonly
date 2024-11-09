# eks-aws-auth-readonly

All eks to group to have eks-readonly

example.

run : kubectl apply -f eks-readonly.yaml

modify the aws-auth configmap

- groups:
  - eks-read 
  rolearn: arn:aws:iam::xxxxxxxxxx:role/xxxxxxxx
  username: eks-read  
