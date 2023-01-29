# CloudLearning

| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |

|table|column|
|-|-|
| a|b|

# CI/CD

Continuous Delivery
1. Jenkins - stages, learn groovy
1. GitLab CI/CD - yaml language, visual
1. GitHub Actions - yaml, deployed and have visual
1. AWS CodeBuild
1. [Azure DevOps](https://azure.microsoft.com/en-us/products/devops) - by Microsoft - yaml, visual (CI/CD integrated tools)
1. Argo
1. Travis CI
1. circleci

Test for the infrastructure:
* Code
* Security
* Costs
Notify (person, team, system...)
Approval management
Protection against parallel executions (**Terraform**)

repo: [awesome-terraform](https://github.com/shuaibiyy/awesome-terraform)
## Terraform related tools
Terraform code check:
* Plan | verify | fmt
* TFLint

Drift
* Terraform refresh
* Driftctl

Security & PaC:
* Tfsec
* Checkov
* Terrascan
* OPA

CI/CD
* Atlantis

Costs:
* Infracost

[Linkedin Webinar](https://www.linkedin.com/video/event/urn:li:ugcPost:7019575359612284928/) by [Brainboard.com](https://www.brainboard.co/)
[Brainboard.com](https://www.brainboard.co/)
# Infrastructure as a Code
* [Terraform](https://www.terraform.io/) by HCL <br>
Support for multi-cloud Azure, AWS and GCP

* Ansible
  Definition

* AWS CloudFormation
* Azure ARM template
  Azure Resource Manager template - creating resource, Json format
* [Pulumi](https://www.pulumi.com/) <br>
Write infrastructure code faster
Pulumi speeds up your inner dev loop for Infrastructure as Code (IaC) by allowing you to use an IDE giving you statement completion, real-time type checking, and interactive documentation out of the box. In addition you can leverage all of the capabilities of the programming language of your choice so you can reduce the total number of lines of code you’re writing.
