# 01 - Evolution of Cloud + Infrastructure as Code

This module doesn't have any corresponding code.
Datacenters in the early 2000s and late 1990s were challenging to start as you needed to deal with them physically. Now you just pay for an on demand resource. Infrastracture is provisioned via APIs and changed the game for scaling. Servers can be created and destroyed in seconds and are short lived and immutable, since they are so easily replaced.

Provisioning Cloud Resources:
GUI, API/CLI, and *Infrastructure as Code* `


# Infrastructure as Code is:

    -Ad hoc scripts
    -Configuration management tools- Manage software that is running after provisioning hardware
    -Server templating tools- Building out a template for what you want to provision to a server
        -AMI - Amazon Machine Image - provisioned from a template, can build all dependencies into the template
    -Orchestration Tools-  (Kubernetes) - Take your code and deploy onto provisioned hardware
    -Provisioning tools - provision cloud resources 
        -Declarative - declare the end state, tool manages what API calls need to be made
        -Imperative - tell the system what and how you want things to happen

IaC Provisioning Tools:
    Cloud Specific - Cloud Formation - Azure Resource Manager - GC Deployment Manager - Focused on provisioning within their specific cloud.
    Cloud Agnostic - Terraform - Pulumi - Able to be used with any cloud providers.


