# Sample Terraform project with best practice

### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

```
terraform-project/
│
├── main.tf
├── variables.tf
├── outputs.tf
│
├── modules/
│   ├── example_module/
│   │   ├── main.tf
│   │   ├── variables.tf
│   │   └── outputs.tf
├── environments/
│   ├── prod/
│   │   ├── main.tf
│   │   ├── variables.tf
│   │   └── outputs.tf
│   │
│   └── dev/
│       ├── main.tf
│       ├── variables.tf
│       └── outputs.tf
│
├── providers.tf
├── terraform.tfvars
└── backend.tf
```

# Project Structure Description

### 1. Root Level
- `main.tf`: Main configuration for the overall infrastructure.
- `variables.tf`: Declaration of variables used throughout the project.
- `outputs.tf`: Definition of output values to be extracted and used elsewhere.
- `providers.tf`: Provider configurations for AWS or any other providers.
- `terraform.tfvars`: Storage for non-sensitive variables or overrides default values.
- `backend.tf`: Specification of the backend configuration for remote state storage.

### 2. Modules
- `example_module/`: The example module.

Each module contains:
- `main.tf`: Configuration for that specific module.
- `variables.tf`: Module-specific variables.
- `outputs.tf`: Output values specific to that module.

### 3. Environments
- `prod/`: Environment-specific configurations for production.
- `dev/`: Environment-specific configurations for development.

Each environment includes:
- `main.tf`: Configuration specific to that environment.
- `variables.tf`: Environment-specific variables.
- `outputs.tf`: Environment-specific outputs.


# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟