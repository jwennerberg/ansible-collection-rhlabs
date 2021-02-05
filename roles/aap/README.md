aap - Ansible Automation Platform
=========

Simple deployments of Red Hat Ansible Automation Platform components

* Ansibe Tower
* Private Automation Hub

Role Variables
--------------

**aap_component** - Ansible Automation Platform (AAP) component to install

*Default:* `tower`

Valid options: `tower`, `automationhub`

*REQUIRED*

**aap_setup_package_url** - AAP install package URL

*Default:* None

*REQUIRED*

**aap_setup_dir** - Path to unpack install package

*Default:* `/opt/automation-platform`

License
-------

Apache-2.0
