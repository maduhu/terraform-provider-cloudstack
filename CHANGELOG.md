## 0.1.1 (Unreleased)

IMPROVEMENTS:

* `cloudstack_customer_gateway`: Add support for using projects [GH-3]

BUG FIXES:

* `cloudstack_instance`: Prevent a potential crash when deleting an instance [GH-7]
* `cloudstack_security_group_rule`: Fix a panic when trying to read a deleted security group [GH-2]

## 0.1.0 (June 20, 2017)

NOTES:

* Same functionality as that of Terraform 0.9.8. Repacked as part of [Provider Splitout](https://www.hashicorp.com/blog/upcoming-provider-changes-in-terraform-0-10/)
