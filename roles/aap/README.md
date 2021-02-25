aap - Ansible Automation Platform
=========

Simple non-production deployments of Red Hat Ansible Automation Platform components

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

**aap_public_ip_name** - Reachable IP or DNS name for automationhub component

*Default:* `ansible_facts.default_ipv4.address`

**aap_setup_dir** - Path to unpack install package

*Default:* `/opt/automation-platform`

**aap_admin_password** - Admin password

*Default:* `demo123`  **PLEASE UPDATE**

**aap_pg_password** - PostgreSQL admin password

*Default:* `demo123`  **PLEASE UPDATE**

License
-------

Apache-2.0
