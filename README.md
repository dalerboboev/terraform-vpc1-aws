# Please copy paste code below


```
module "vpc1" {
    source = "dalerboboev/vpc1/aws
    region        = "eu-west-2"
    cidr_block    = "10.0.0.0/16"
    public_cidr1  = "10.0.101.0/24"
    public_cidr2  = "10.0.102.0/24"
    public_cidr3  = "10.0.103.0/24"
    private_cidr1 = "10.0.1.0/24"
    private_cidr2 = "10.0.2.0/24"
    private_cidr3 = "10.0.3.0/24"
    tags = {
      Team = "2"
    }
}

```
