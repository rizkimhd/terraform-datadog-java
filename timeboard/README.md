terraform-datadog-timeboard-java
=================

Terraform module to create Datadog Timeboard for Java.



Usage
-----

```hcl
module "timeboard_java_beical-app" {
  source            = "github.com/traveloka/terraform-datadog-java//timeboard"
  product_domain    = "BEI"
  cluster           = "beical-app"
  garbage_collector = "PS" // Either PS or CMS 
}
```

Terraform Version
-----------------

This module was created using Terraform 0.11.7. 
So to be more safe, Terraform version 0.11.7 or newer is required to use this module.

Authors
-------

* [Karsten Ari Agathon](https://github.com/karstenaa)

License
-------

Apache 2 Licensed. See LICENSE for full details.