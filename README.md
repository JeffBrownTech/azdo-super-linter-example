# azdo-super-linter-example

This repo contains an example of incorporating Super-Linter into Azure DevOps pipeline, more specifically testing an ARM template. The azure-pipelines.yml file also include additional steps for validating the ARM template and performing a deployment.

If you wish to try this out, be sure to make the following changes:

- Add a storage account name to the azuredeploy.parameters.json file
- In the azure-pipelines.yml file:
-- Replace instances of {resource group name} with the name of the resource group to deploy to
-- Replace instances of {enter service connection} with the name of your Azure DevOps service connection

Read more about including Super-Linter in Azure DevOps Pipelines in my blog post:

[Jeff Brown Tech | Deploy Super-Linter in Azure DevOps Pipelines](https://jeffbrown.tech/super-linter-azure-devops)