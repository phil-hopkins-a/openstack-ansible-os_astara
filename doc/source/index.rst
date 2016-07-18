os_astara Docs
============

Ansible role for deploying OpenStack Astara and all of its corresponding
services.

This role will install the following:
   * orchestrator

This role will disable/remove the following:
   * neutron-l3-agent
   * neutron-dhcp-agent
   * neutron-metadata-agent
   * neutron-lbaas-agent
   * other neutron agents ?

Basic Role Example
^^^^^^^^^^^^^^^^^^

.. code-block:: yaml

    - role: "os_astara"
      ROLE_VARS...
