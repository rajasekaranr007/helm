**Follow the below steps to install helm packages:**

1. Add helm repo

helm3 repo add mediawikiapp https://rajasekaranr007.github.io/helm

**Install mysql:**

helm install mediawikiapp/mysql --name=my-namespace

**Install mediawiki:**

helm install mediawikiapp/mediawiki --name=my-namespace

