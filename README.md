# Terraform Plan CI Pipeline

GitHub Actions workflow that runs `terraform fmt`, `init`, `validate` and
`plan` on every push, then uploads the plan as a build artifact.

## Local usage
    terraform init
    terraform plan
