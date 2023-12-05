Overview
--------

* Terraform resource models for bootstrapping core infra
* Containerized app templates and build/deploy examples
* Config management examples

The original goal was a personal cloud development environment for
learning and experimentation. Along the way I sought to capture reusable
patterns for cloud-based development and operations.


Cloud Infra
-----------

* Terraform code organization
* Custom VM images
* Netowrking and IAM
* Live infrastructure ops

2023-12-04: DEMO ENVIRONMENTS CONVERSION IN PROGRESS (PRIVATE)
* [cloud-aws](https://github.com/coreinfra-org/cloud-aws)
* [cloud-gcp](https://github.com/coreinfra-org/cloud-gcp)
* [cloud-linode](https://github.com/coreinfra-org/cloud-linode)
* [cloud-ocean](https://github.com/coreinfra-org/cloud-ocean)
* [cloud-vultr](https://github.com/coreinfra-org/cloud-vultr)


Config Management
-----------------

* Demonstrate key feature of Ansible
* Demonstrate how to organize Ansible playbooks, inventory, roles, vars, etc
* The live demo currently (2023-12-04) depends on cloud resources in AWS
  (for example VM instances with particular tags)

* [demo-ansible](https://github.com/coreinfra-org/demo-ansible)


Base App Templates
------------------

* [app-base-c](https://github.com/coreinfra-org/app-base-c)
* [app-base-golang](https://github.com/coreinfra-org/app-base-golang)
* [app-base-java](https://github.com/coreinfra-org/app-base-java)
* [app-base-nodejs](https://github.com/coreinfra-org/app-base-nodejs)
* [app-base-python](https://github.com/coreinfra-org/app-base-python)


Demo App Templates
------------------

* app-flask-auth0
* app-flask-authlib
* app-flask-bootstrap
* app-flask-golinks
* app-flask-ipaddr
* app-flask-multitest
* app-flask-openai
* app-flask-wiki
* app-hugo-site
