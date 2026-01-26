# Challenge 1
```bash
We have 2 managed nodes that are part of different DNS domains with a distinct DNS server for each. Using the sample resolv.conf located at ~/playbooks/dns, generate a new resolv.conf file and copy it to the respective nodes using the template module.

Update the template file located at ~/playbooks/dns/templates/resolv.conf.j2 to print the nameserver details as shown in the sample_resolv.conf file. DNS server to be used is specified in the inventory file.
Use this template to create a playbook called update_dns_server.yml. This playbook should generate the new resolv.conf and copy to the temp file /tmp/resolv.conf on the respective nodes.

Goal:
Get familiar with Jinja2 templating and the usage of template Ansible module
```
# Challenge 2
```bash
We have two nodes that are managed by Ansible. There is an inventory file ~/playbooks/inventory on Ansible controller which has all these two nodes added. Create a playbook ~/playbooks/blocks.yml on Ansible controller to install httpd web server and start its service.

Create the playbook using blocks to logically group the tasks (installation and service start).
Goal:
Test your knowledge about Ansible blocks, yum and service modules
```
# Challenge 3
```bash
Using an Ansible playbook install firewalld on node00 node, start its service as well. Name the playbook as firewall.yml and keep it under ~/playbooksand also white list node01 host IP address 172.20.1.101 on node00.
Goal:
Get familiar with ansible firewalld module
```