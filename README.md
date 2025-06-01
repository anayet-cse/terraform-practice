# terraform-practice

## Terraform

Terraform is a tool that helps you automatically set up and manage your cloud infrastructure (like servers, databases, networks, etc.) using code instead of doing it manually.


## What Does It Do?

Terraform lets you:  
- **Create** infrastructure (e.g., virtual machines, databases, networks)  
- **Change** existing setups safely  
- **Destroy** infrastructure when you're done  

Describe everything in simple text files (in a language called **HCL** – HashiCorp Configuration Language), and Terraform takes care of the rest.


## Example

Let’s say you want to set up:  
- 2 virtual machines on AWS  
- A database  
- A network connecting them  

Instead of doing it manually on the AWS website, you write this in a Terraform file.Then run.

## Why Use Terraform?

| Benefit                       | Explanation                                              |
|------------------------------|----------------------------------------------------------|
| Infrastructure as Code (IaC) | Everything is version-controlled and repeatable           |
| Reusable & Shareable       | Same config works across teams, projects, or cloud providers |
| Multi-Cloud                | Works with AWS, Azure, GCP, and more                      |
| Safe Changes               | Shows a plan before making any updates                   |

## Providers

Terraform works with many platforms, not just cloud. A few examples:

- **AWS**, **Azure**, **Google Cloud**
- **Docker**
- **Kubernetes**
- **GitHub**
- **Databases**, **DNS providers**, and more

## Common Terraform Commands

| Command             | What It Does                                 |
|---------------------|-----------------------------------------------|
| `terraform init`    | Initializes project, downloads providers      |
| `terraform plan`    | Shows what will change (preview)              |
| `terraform apply`   | Makes actual changes to infrastructure        |
| `terraform destroy` | Deletes all Terraform-managed resources       |

## What is Terraform State?

Terraform uses a **state file** (`terraform.tfstate`) to track the current state of your infrastructure — like a record of what it has created and what exists.

### Why It's Needed:

- Remembers what resources are already created  
- Helps Terraform compare what you have vs. what you want (from `.tf` files)  
- Speeds up the `plan` and `apply` process  
- Avoids accidental re-creation of resources  

## Summary

| Term      | Meaning                                                            |
|-----------|--------------------------------------------------------------------|
| **Terraform** | Tool for automating infrastructure setup                          |
| **IaC**       | Infrastructure as Code — using code instead of clicking          |
| **HCL**       | HashiCorp Configuration Language (what you write Terraform files in) |

Terraform is like **"Infrastructure as Code (IaC)"** – Describe what you need in a file, and Terraform makes it happen in the cloud.



