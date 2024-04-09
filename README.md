# API REST - Foundation IaC
<br>
<img src="https://drive.google.com/uc?export=view&id=1spIcWkUkR1Ws0HZCPW1dn5fxL87BSCEp" width="1000">
<br>

Repositório de fundação do projeto API REST. Ele se propõe a criar todas as estruturas básicas/fundamentais que serão necessárias para o provisionamento do projeto principal. Localizado neste repositório: https://github.com/dellabeneta/ntconsult-iac-api. 

<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_aws"></a> [aws](#requirement\_aws) | 5.44.0 |
| <a name="requirement_digitalocean"></a> [digitalocean](#requirement\_digitalocean) | 2.36.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | 5.44.0 |
| <a name="provider_digitalocean"></a> [digitalocean](#provider\_digitalocean) | 2.36.0 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [aws_s3_bucket.bucket](https://registry.terraform.io/providers/hashicorp/aws/5.44.0/docs/resources/s3_bucket) | resource |
| [digitalocean_certificate.cert](https://registry.terraform.io/providers/digitalocean/digitalocean/2.36.0/docs/resources/certificate) | resource |
| [digitalocean_domain.domain](https://registry.terraform.io/providers/digitalocean/digitalocean/2.36.0/docs/resources/domain) | resource |
| [digitalocean_project.project](https://registry.terraform.io/providers/digitalocean/digitalocean/2.36.0/docs/resources/project) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_bucket_backend_name"></a> [bucket\_backend\_name](#input\_bucket\_backend\_name) | n/a | `string` | `"ntconsult-terraform-state-backend"` | no |
| <a name="input_do_token"></a> [do\_token](#input\_do\_token) | n/a | `string` | n/a | yes |
| <a name="input_project_description"></a> [project\_description](#input\_project\_description) | n/a | `string` | `"This project organizes the resources created by the foundation IaC."` | no |
| <a name="input_project_name"></a> [project\_name](#input\_project\_name) | n/a | `string` | `"Foundation"` | no |
| <a name="input_project_purpose"></a> [project\_purpose](#input\_project\_purpose) | n/a | `string` | `"Service or API"` | no |

## Outputs

No outputs.
<!-- END_TF_DOCS -->