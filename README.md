# Terraform_Azure
Tony's Terraform Azure lab training

This is a fork of a Terraform lab that deploys a VM environment to Azure.

You'll need to:
* [Download the terraform binary](https://www.terraform.io/downloads.html) 
* [Download and install VSCode](https://code.visualstudio.com/download) 
* [Download and install Git for Windows (or mac)](https://git-scm.com/downloads)
* [Download and install Azure CLI for Windows (or mac)](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest)
* Have an Azure subscription and know your credentials. (30 day free trial available)

In VSCode, you'll want the Terraform, Azure Terraform, and Azure Terraform Autocomplete extensions.

Once all of that is installed and set up, you'll want to log your system into your Azure portal account via this command:
```
az login
```

I have played with commands to plan (preview what your script will do)

```
terraform plan
```

And commands to actually deploy

```
terraform apply
```

And commands to tear down (destroy what you built)

```
terraform destroy
```

You can use a workspace to use a named .tfcreate file instead of the default terraform.tfcreate

```
terraform workspace create
```
