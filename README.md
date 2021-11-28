# HAProxy_configuration_Ansible

I've created an Ansible playbook to Configure Reverse Proxy i.e. Haproxy and update it's configuration file automatically on each time new Managed node (Configured With Apache Webserver) join the inventory. Ansible is a great tool for Configuration Management & Automation.

To know more about Ansible, read my blog:\
https://samar10pratapsingh.medium.com/case-study-ansible-making-openstack-simple-b765a89bfbb9

## Project Description
🔰 Write an Ansible PlayBook that does the following operations in the managed nodes:\
🔹 Configurs HAProxy one Managed Node\
🔹 Configures Apache Webserver (HTTPD) on other Managed Nodes\
🔹 It should automatically update the Haproxy Configuration file (configured on one of the Managed Node) each time a new Managed Node joins th inventory for webservice configuration.

Hope you guys liked it! Thanks for reading, I'll meet you in the next one. 😊
