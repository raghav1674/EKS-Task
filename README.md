# EKS-Task


## What is Amazon EKS?

Amazon EKS is a managed service that helps make it easier to run Kubernetes on AWS. Through EKS, organizations can run Kubernetes without installing and operating a Kubernetes control plane or worker nodes. Simply put, EKS is a managed containers-as-a-service (CaaS) that drastically simplifies Kubernetes deployment on AWS.



<img src= "https://www.alfresco.com/sites/www.alfresco.com/files/2018/Nov/amazoneks_twitter.jpg?_buster=CFwpRD-B" />
 
 
 
 ## DEPLOYMENT OF JOOMLA AND MYSQL OVER EKS CLUSTER AND USING EFS AS A PVC :
 
 
 ## EKS CLSUTER
 
 
 [EKS CLUSTER FILE](https://github.com/raghav1674/EKS-Task/blob/master/create_cluster.yml)
 
 ## EFS-PROVISIONER
   
   
  1.[EFS-PROVISIONER](https://github.com/raghav1674/EKS-Task/blob/master/create_efs_provisioner.yml)
  
 
  2.[ROLE BINDING FOR EFS-PROVISIONER](https://github.com/raghav1674/EKS-Task/blob/master/create_rbac.yml)
  
  
  ## SECRET RESOURCE FOR MYSQL ROOT PASSWORD
  
  [SECRET](https://github.com/raghav1674/EKS-Task/blob/master/create_secret.yml)
 
 ## STORAGE CLASS WITH OUR OWN CREATED EFS-PROVISIONER:
 
 1.[STORAGE CLASS AND THE PVC ](https://github.com/raghav1674/EKS-Task/blob/master/create_storage.yml)


## JOOMLA DEPLOYMENT 

[JOOMLA DEPLOYMENT](https://github.com/raghav1674/EKS-Task/blob/master/create_joomla_deployment.yml)

## MYSQL DEPLOYMENT

[MYSQL DEPLOYMENT](https://github.com/raghav1674/EKS-Task/blob/master/create_sql_deployment.yml)
 
 
 


