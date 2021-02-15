# Deploy templates

##deploy-function-app.yml
Deploys a function app that has been published in zip form.

| Paramter | Example | Description |
|----------|---------|-------------|
|serviceConnection | azureRmConnection | The Azure pipeline service connection which is used to perform the deployment |
|appName           | ws-emugps         | The name of the function app that the zip will be deployed into |
|appZipFile        | *.zip             | The name of the published zip file to be deployed |
|resourceGroup     | ws-emugps         | The name of the resoruce group that the function app is in and the service connection has permisions to change |

##deploy-terraform.yml
##format-names.yml
##funcational-testing.yml
##get-artifact.yml
##performance-testing.yml
##smoke-testing.yml
