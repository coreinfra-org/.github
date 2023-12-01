Overview
--------

This github org hosts templates for bootstrapping cloud infra projects,
including terraform models for core infra components, containerized application
build/deploy templates, and examples for system configuration management.

The original goal was a personal cloud development environment for
learning and experimentation. Along the way I sought to capture reusable
patterns for cloud-based development and operations.


Cloud infra
-----------

Patterns for organizing Terraform code, building custom images, configuring
networking and access control, and managing the live cloud infra using
various providers.

* cloud-aws/
* cloud-gcp/
* cloud-linode/
* cloud-ocean/
* cloud-vultr/


Config Management
-----------------

An example config structure and demo of the key features of Ansible.
There are many ways to configure and run Ansible. This demo serves as a
sort of "framework" for how one can structure an Ansible directory tree
with inventory, playbooks, roles, variables, plugins, etc.

* demo-ansible/


Containerized App Templates
---------------------------

These are intended as leverage points for new containerized app development
environments. The goal is to enable rapid prototyping of a new application
with a consistent development lifecycle.

* app-base-c
* app-base-golang
* app-base-java
* app-base-nodejs
* app-base-python

<!--
TODO(sbostick):
* app-flask-auth0
* app-flask-authlib
* app-flask-bootstrap
* app-flask-golinks
* app-flask-ipaddr
* app-flask-multitest
* app-flask-openai
* app-flask-wiki
* app-hugo-site
-->
