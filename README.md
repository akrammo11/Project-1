📦 Terraform Infrastructure as Code with Jenkins Pipeline
This repository contains a modular Infrastructure as Code (IaC) setup using Terraform, designed to provision and manage cloud resources efficiently. It also includes a Jenkinsfile to automate the infrastructure deployment using a CI/CD pipeline.

🔧 Contents
main.tf – Defines the core infrastructure resources.

provider.tf – Specifies the cloud provider and authentication details.

variable.tf – Declares input variables for flexible configuration.

output.tf – Outputs key resource attributes after deployment.

Jenkinsfile – CI/CD pipeline script for automated provisioning via Jenkins.

🚀 Features
Modular and reusable Terraform code.

CI/CD integration using Jenkins for automated deployment.

Environment-independent infrastructure provisioning.

Scalable and maintainable configuration.

🛠️ Prerequisites
Terraform CLI installed

Jenkins server with necessary plugins

Cloud provider credentials (e.g., AWS access/secret keys if using AWS)
