# terraform-module-november

## Copy and paste following block

```hcl
module "november" {
  source  = "nazikmusa/november/module"
  version = "3.0.0"
  region = "us-east-1"
  vpc_cidr = "10.0.0.0/16
  subnet_cidr = "10.0.1.0/24"
  igw_name = "Kaizen" 
  }
  ```
  


module "november-2024" { source = "kaizenacademy/november-2024/module" version = "3.0.0" region = "us-east-1" vpc_cidr = "10.0.0.0/16" subnet_cidr = "10.0.1.0/24" igw_name = "Kaizen" }