**Follow the below steps to install helm packages:**

**Add helm repo in your repository list**

helm3 repo add mediawikiapp https://rajasekaranr007.github.io/helm

helm3 repo list 

**Install mysql:**

helm install mediawikiapp/mysql --name=my-namespace

**Install mediawiki:**

helm install mediawikiapp/mediawiki --name=my-namespace

