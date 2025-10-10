Some meaningful Terraform content about creating an AWS resource

*S3 Bucket*

```
provider "aws" { region = "us-east-1" }
resource "aws_s3_bucket" "example" {
  bucket = "my-example-bucket-123"
  acl    = "private"
}
```
