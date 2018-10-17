# Ansible VMware Sample Playbooks for handling HTTP APIs


Following repos show how Ansible can be utilized to consume VMware HTTP APIs.

Requirements
------------

VMware HTTP APIs are supported in vCenter 6.5 and onwards. So, in order to use these playbooks you need to have vCenter version greater than equal to 6.5.

If you are going to use [Pyvmomi](https://github.com/vmware/pyvmomi) based (XMLRPC based) [modules](https://docs.ansible.com/ansible/latest/modules/list_of_cloud_modules.html#vmware) then you need to install ``Pyvmomi`` using ``pip install pyvmomi``.


Examples
--------

Example Ansible playbook to manage VMware using HTTP APIs:

- [Get a list of all Datacenters available](../master/get_all_datacenters.yml)
- [Get a list of all Clusters available](../master/get_all_clusters.yml)
- [Get a list of all ESXi hosts available](../master/get_all_hosts.yml)
- [Get a list of all Datastores available](../master/get_all_datastores.yml)
- [Get a list of all Network available](../master/get_all_networks.yml)
- [Get a list of all Virtual machine available](../master/get_all_vms.yml)
- [Get a list of all categories available](../master/get_all_categories.yml)
- [Get a list of all tags available](../master/get_all_tags.yml)
- [Get information about the given Cluster](../master/get_cluster_info.yml)


Caveats
-------

Currently, these APIs are under development so not all features are available in vCenter server as a part of API.


Links
-----

[Ansible VMware Documentation](https://docs.ansible.com/ansible/latest/vmware/index.html)


vBrownBag videos link
---------------------

* [VMware vSphere and Ansible From Zero to Useful](https://www.youtube.com/watch?v=0_qwOKlBlo8) by [@arielsanchezmor](https://twitter.com/arielsanchezmor)
