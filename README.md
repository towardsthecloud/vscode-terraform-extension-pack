# AWS Terraform Extension Pack

This is a collection of extensions that I've curated in this vscode extension pack to help you build, deploy and manage your Terraform modules.

<!-- TIP-LIST:START -->
> [!TIP]
> **Stop AWS bill surprises before they ship.**
>
> Most infrastructure changes look harmless until next month's AWS bill lands. [CloudBurn](https://cloudburn.io) analyzes the cost impact of your Terraform changes right in the GitHub pull request, so expensive mistakes get caught during code review, while a fix is still a one-line change.
>
> <a href="https://github.com/marketplace/cloudburn-io"><img alt="Install CloudBurn from GitHub Marketplace" src="https://img.shields.io/badge/Install%20CloudBurn-GitHub%20Marketplace-brightgreen.svg?style=for-the-badge&logo=github"/></a>
>
> <details>
> <summary>💰 <strong>Set it up once, then never be surprised by AWS costs again</strong></summary>
> <br/>
>
> 1. **Install the free [Terraform Plan PR Commenter GitHub Action](https://github.com/marketplace/actions/terraform-plan-pr-commenter)** in the repository where you build your AWS Terraform infrastructure
> 2. **Then install the [CloudBurn GitHub App](https://github.com/marketplace/cloudburn-io)** on the same repository
>
> From then on, every PR with infrastructure changes gets a comment with your Terraform plan analysis, and CloudBurn adds a cost report next to it:
> - **Monthly cost impact**: whether this change raises or lowers your AWS bill, and by how much
> - **Per-resource breakdown**: which resources drive the change, old versus new monthly cost
> - **Region-aware pricing**: rates match the region your infrastructure actually deploys to
>
> Cost review happens inside code review, so you optimize as you code, while the context is still fresh.
>
> CloudBurn is free during beta. After launch, a free Community plan (1 repository, unlimited users) stays available.
>
> </details>
<!-- TIP-LIST:END -->

## Included Extensions

This extension pack includes the following VS Code extensions:

1. **Betajob Terraform**: Semantic highlighting support for Terraform, and more to come...
2. **Amazon Web Services Toolkit for VS Code**: Offers tools for working with AWS services
3. **IAM Actions Snippets**: Adds autocomplete and snippets for AWS IAM policy actions in Terraform
4. **AWS IAM Service Principal Snippets**: Autocompletion for AWS service principals.
5. **[AWS IAM Policy Debugger](https://github.com/towardsthecloud/vscode-iam-policy-debugger)**: Validate IAM policies, explain access requests and run saved regression scenarios. Unpublished development preview; this pack update must be released after the debugger is available in the Marketplace.
6. **HashiCorp Terraform**: Official extension for Terraform language support
7. **IntelliCode**: AI-assisted development features from Microsoft

## Installation

1. Open Visual Studio Code
2. Go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X on macOS)
3. Search for "AWS Terraform Extension Pack"
4. Click "Install"

## Usage

Once installed and configured, you can start using the extensions right away in your Terraform projects. The extensions will automatically enhance your development environment with features like code completion, linting, formatting, and more.

For specific usage instructions for each extension, please refer to their individual documentation.

---
## Feedback and Contributions

If you have any feedback or suggestions for improving this extension pack, please open an issue on the [GitHub repository](https://github.com/towardsthecloud/vscode-terraform-extension-pack/issues). Contributions are always welcome!

Happy building with Terraform!

## Author

[Danny Steenman](https://towardsthecloud.com/about)

[![](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/towardsthecloud)
[![](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/dannysteenman)
[![](https://img.shields.io/badge/GitHub-2b3137?style=for-the-badge&logo=github&logoColor=white)](https://github.com/towardsthecloud)
