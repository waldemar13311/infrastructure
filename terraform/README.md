```bash
tofu -chdir=terraform init
tofu -chdir=terraform apply -parallelism=1
tofu -chdir=terraform destroy -parallelism=1
```
