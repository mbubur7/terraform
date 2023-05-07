# Terraform

### Create a folder with name "terraform_tws"

```
terraform --version
```

add the extension on VS code Terraform, HashiCorp Terraform

create a file **named main.tf**
```
resource "local_file" "mbubur" { 
filename = "mbubur_text.txt"
content = "Hi This Mahbubur R."
}
```

Create a local file using terraform in main.tf open an integrated temminal

initilised the terraform using cmd and apply
```
terraform init
```
terraform apply then type **yes**

output will be created a file with contained above text

To validate the code 

```
terraform validate
```

