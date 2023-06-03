# What is Terraform
Terraform: infrastructure as a code

1. Multiple Cloud Platforms
2. Configuration for Humans
3. Track Resources with State

From Terraform tutorial:
"Infrastructure as code (IaC) tools allow you to manage infrastructure with configuration files rather than through a graphical user interface. IaC allows you to build, change, and manage your infrastructure in a safe, consistent, and repeatable way by defining resource"

# Terraform configuration language
"Terraform's configuration language is declarative, meaning that it describes the desired end-state for your infrastructure, in contrast to procedural programming languages that require step-by-step instructions to perform tasks. Terraform providers automatically calculate dependencies between resources to create or destroy them in the correct order."

- DESCRIBE END-STATE for my Infrastructure
- Provides auto calculate of deps between resources for creating and destroying in the order

# How to deploy my infrastructure using Terraform configuration language


- Scope - Identify the infrastructure for your project.
- Author - Write the configuration for your infrastructure.
- Initialize - Install the plugins Terraform needs to manage the infrastructure.
- Plan - Preview the changes Terraform will make to match your configuration.
- Apply - Make the planned changes.


"Terraform keeps track of your real infrastructure in a state file, which acts as a source of truth for your environment. Terraform uses the state file to determine the changes to make to your infrastructure so that it will match your configuration."
