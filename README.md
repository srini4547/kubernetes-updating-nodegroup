# kubernetes-updating-nodegroup

# Pre-Requisites
    EKS-cluster
# Step:1
  Need to create cluster with one node group. Here I created nodegroup with the name of "eksdemo-ng-public1".
  
  ![image](https://user-images.githubusercontent.com/58024415/116837415-00da4900-abe8-11eb-89e5-fe2293cc1cc4.png)
# Step:2 
  Deploy application using below command
    
    kubectl apply -f deployment.yml
  ![image](https://user-images.githubusercontent.com/58024415/116837541-7f36eb00-abe8-11eb-86ad-2593f7ab4285.png)
# Step:3
  Need to create new node group using below command
    
    
4.  
