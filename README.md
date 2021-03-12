go build -o build/bin/app

terraform init infra

terraform plan infra

terraform apply infra

terraform destroy infra