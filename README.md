# PPT-204
# Puppet Certified Professional Study Guide

Online resources that will help you prepare for taking the Puppet Professional Certification exam.

## Exam Objectives

### 1. Language

#### Identify Style Guide recommendations
* [The Puppet Language Style Guide](https://docs.puppet.com/puppet/latest/style_guide.html)
* [puppet-lint](http://puppet-lint.com/)
* [metadata-json-lint](https://github.com/voxpupuli/metadata-json-lint)

#### Describe language features
* [Language: Basics](https://docs.puppet.com/puppet/latest/reference/lang_summary.html)
* [Language: Reserved Words and Acceptable Names](https://docs.puppet.com/puppet/latest/reference/lang_reserved.html)
* [Language: Resources](https://docs.puppet.com/puppet/latest/reference/lang_resources.html)
* [Language: Advanced Resources](https://docs.puppet.com/puppet/latest/lang_resources_advanced.html)
* [Language: Relationships and Ordering](https://docs.puppet.com/puppet/latest/reference/lang_relationships.html)
* [Langauge: Resource Defaults](https://docs.puppet.com/puppet/latest/reference/lang_defaults.html)
* [Language: Variables](https://docs.puppet.com/puppet/latest/reference/lang_variables.html)
* [Language: Tags](https://docs.puppet.com/puppet/latest/reference/lang_tags.html)
* [Language: Facts and Built-in Variables](https://docs.puppet.com/puppet/latest/reference/lang_facts_and_builtin_vars.html)
* [Language: Scope](https://docs.puppet.com/puppet/latest/reference/lang_scope.html)
* [Language: Conditional Statements](https://docs.puppet.com/puppet/latest/reference/lang_conditional.html)
* [Language: Iteration and loops](https://docs.puppet.com/puppet/latest/reference/lang_iteration.html)
* [Language: Lambdas](https://docs.puppet.com/puppet/latest/reference/lang_lambdas.html)
* [Language: Resource collectors](https://docs.puppet.com/puppet/latest/reference/lang_collectors.html)
* [Language: Virtual resources](https://docs.puppet.com/puppet/latest/reference/lang_virtual.html)
* [Language: Expressions](https://docs.puppet.com/puppet/latest/reference/lang_expressions.html)
* [Language: Functions](https://docs.puppet.com/puppet/latest/reference/lang_functions.html)
* [ntp-puppet-4-language-update](https://puppet.com/blog/ntp-puppet-4-language-update)

#### Identify the core resource types
* [Type Reference](https://docs.puppet.com/references/latest/type.html)

#### Demonstrate knowledge of classes and defines
* [Language: Classes](https://docs.puppet.com/puppet/latest/reference/lang_classes.html)
* [learning Puppet - Defined Types](https://docs.puppet.com/learning/definedtypes.html)
* [Language: Defined Resource Types](https://docs.puppet.com/puppet/latest/reference/lang_defined_types.html)

### 2. Modules

#### Describe how to use modules from the Forge
* [Installing Modules](https://docs.puppet.com/puppet/latest/reference/modules_installing.html)

#### Demonstrate knowledge of module structure
* [Module Fundamentals](https://docs.puppet.com/puppet/latest/reference/modules_fundamentals.html)
* [Documenting Modules](https://docs.puppet.com/puppet/latest/reference/modules_documentation.html)

#### Identify module authoring best practices
* [Beginner's Guide to Modules](https://docs.puppet.com/guides/module_guides/bgtm.html)
* [Best Practices for Building Puppet Modules](https://puppet.com/blog/best-practices-building-puppet-modules)

### 3. Using Puppet

#### Describe environments in Puppet
* [About environments](https://docs.puppet.com/puppet/latest/environments_about.html)
* [Creating environments](https://docs.puppet.com/puppet/latest/environments_creating.html)
* [Environments isolations](https://docs.puppet.com/puppet/latest/environment_isolation.html)
* [Git Workflow and Puppet Environments](https://puppetlabs.com/blog/git-workflow-and-puppet-environments?_ga=1.219608607.74181882.1427164782)
* [Environments and Puppet's HTTPS Interface](https://docs.puppetlabs.com/puppet/latest/reference/environments_https.html)

#### Describe the lifecycle of a Puppet run
* [Learning Puppet — Basic Agent/Master Puppet](https://docs.puppetlabs.com/learning/agent_master_basic.html)
* [Subsystems: Agent/Master HTTPS Communications](https://docs.puppetlabs.com/puppet/latest/reference/subsystem_agent_master_comm.html)
* [Subsystems: Catalog Compilation](https://docs.puppetlabs.com/puppet/latest/reference/subsystem_catalog_compilation.html)

#### Describe Puppet ecosystem component usage
* [A New Era of Application Services at Puppet Labs](https://puppetlabs.com/blog/new-era-application-services-puppet-labs)
* [Subsystems: Agent/Master HTTPS Communications](https://docs.puppetlabs.com/puppet/latest/reference/subsystem_agent_master_comm.html)
* [Subsystems: Catalog Compilation](https://docs.puppetlabs.com/puppet/latest/reference/subsystem_catalog_compilation.html)
* [PuppetDB Overview](http://docs.puppetlabs.com/puppetdb/latest/)

#### Describe how to configure a Puppet master
* [Configuration: How Puppet is Configured](https://docs.puppetlabs.com/puppet/latest/reference/config_about_settings.html)
* [Puppet Server: Configuration](https://docs.puppet.com/puppetserver/latest/configuration.html)

### 4. Puppet Internals


#### Describe the purpose of types and providers
* [Custom Types](https://docs.puppetlabs.com/guides/custom_types.html)
* [Provider Development](https://docs.puppetlabs.com/guides/provider_development.html)

#### Describe Puppet’s use of SSL certificates
* [Certificates and Security](http://projects.puppetlabs.com/projects/1/wiki/certificates_and_security)
* [Puppet Server: External CA Configuration](https://docs.puppetlabs.com/puppetserver/latest/external_ca_configuration.html)
* [SSL Configuration: External CA Support](https://docs.puppetlabs.com/puppet/latest/reference/config_ssl_external_ca.html)
* [SSL Configuration: Autosigning Certificate Requests](https://docs.puppetlabs.com/puppet/latest/reference/ssl_autosign.html)

### 5. Classification

#### Describe classification
* [Getting Started with Classification](https://docs.puppetlabs.com/pe/latest/console_classes_groups_getting_started.html)
* [Puppet: Assigning Configurations to Nodes](https://docs.puppetlabs.com/pe/latest/puppet_assign_configurations.html)
* [Grouping and Classifying Nodes](https://docs.puppetlabs.com/pe/latest/console_classes_groups.html)
* [Language: Node definitions](https://docs.puppet.com/puppet/latest/lang_node_definitions.html)
* [Writing external node classifiers](https://docs.puppet.com/puppet/latest/nodes_external.html)

### 6. Console

#### Describe Node Manager
* [Puppet: Assigning Configurations to Nodes](https://docs.puppetlabs.com/pe/latest/puppet_assign_configurations.html)
* [Grouping and Classifying Nodes](https://docs.puppetlabs.com/pe/latest/console_classes_groups.html)
* [Making Changes in the Node Classifier](https://docs.puppetlabs.com/pe/latest/console_classes_groups_making_changes.html)

#### Describe RBAC
* [Role-based Access Control](https://docs.puppetlabs.com/pe/latest/rbac_intro.html)
* [Connecting PE to an External Directory Service](https://docs.puppetlabs.com/pe/latest/rbac_ldap.html)
* [RBAC Permissions](https://docs.puppetlabs.com/pe/latest/rbac_permissions.html)
* [Creating and Managing Users and User Roles](https://docs.puppetlabs.com/pe/latest/rbac_user_roles.html)

#### Describe reporting capabilities in PE Console
* [Viewing Reports and Inventory Data](https://docs.puppetlabs.com/pe/latest/console_reports.html)
* [Monitor current infrastructure state](https://docs.puppet.com/pe/latest/CM_overview.html)

### 7. Ecosystem

#### Describe the purpose of PuppetDB
#### Demonstrate knowledge of Hiera
#### Describe the usage of MCollective
#### Demonstrate knowledge of Facter
#### Describe the purpose of Code Manager

