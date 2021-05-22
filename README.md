**Follow the below steps to install helm packages:**

**Add helm repo in your repository list**

$helm3 repo add mediawikiapp https://rajasekaranr007.github.io/helm

$helm3 repo list

**Update helm repo:**

$helm repo update 

**Install mysql:**

helm install mysql mediawikiapp/mysql -n my-namespace

**Install mediawiki:**

helm install mediawiki mediawikiapp/mediawiki -n my-namespace

Validate the resporces with kubectl command.

kubectl get all -n my-namespace


**Note: **
  
  Here we are using PVC using Azur disks, if you are using other cloud you have to update PVC details.
