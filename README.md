# Idea

This project aims to develop a sophisticated Infrastructure as Code (IaC) tool similar to Terraform or Pulumi, but entirely in Python. The primary goal is to explore the best methods for quickly building custom providers.

# Problems I wish to solve

- No need to learn Go to contribute to the core library.
- Create a minimalist provider builder to make development as easy as possible.
- Implement a built-in feature for exporting resources, allowing providers to list and export all existing resources as a configuration file.
- Provide an easy way to add custom state backends.
- Enable automatic resource imports based on rules, such as looking up IDs by name.
- Building user-friendly plans.

# Plan

- [ ] Build a filesystem provider to provision files as a proof of concept.
- [ ] Develop a configuration level similar to Pulumi’s class definitions.
- [ ] Design apply and destroy functionality.
- [ ] Build a filesystem backend.
- [ ] Create a simple diff mechanism.
- [ ] Design plan functionality.
- [ ] Integrate Pydantic-like schema validation.
- [ ] Implement secrets management functionality.
- [ ] Add state encryption capabilities.
- [ ] Incorporate dependency resolution into the configuration.
