Role Name
=========

Install teleport access server


Role Variables
--------------

	node_name: teleport-access-server
	auth_token: 7d8ae42392ae8b7503dd3b76ea76aca696
	cluster_name: teleport-demo
	proxy_node_token: 7d8ae42392ae8b7503dd3b76ea76
	web_listen_addr: 10.0.0.10:3080
	ca_pin: sha256:829e6b3e91314b0e2bc77c8b592c7280670ba4b896e897060ef1a79dbe241a4a

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: teleport-authen-node }

