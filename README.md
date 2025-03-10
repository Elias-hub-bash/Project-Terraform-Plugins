Terraform Plug-in Based Architecture

Terraform relies on plugins called "providers" to interact with remote systems and expand functionality. 
Terraform configurations must declare which providers they require so that Terraform can install and use them. 
This is performed within a Terraform configuration block.

Terraform Providers are plugins that implement resource types for particular clouds, platforms and generally speaking any remote system with an API. 
Terraform configurations must declare which providers they require, so that Terraform can install and use them. 
Popular Terraform Providers include: AWS, Azure, Google Cloud, VMware, Kubernetes and Oracle.

 1: View available Terraform Providers
 2: Install the Terraform AWS Provider
 3: View installed and required providers
