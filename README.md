### Let's Encrypt 
To enable HTTPS on your website, you need to get a certificate (a type of file) from a Certificate Authority (CA). Let’s Encrypt is a CA. 

---
In this template we will create an Ansible playbook to install nginx, Let’s Encrypt, creating a certificate and the basic nginx configurations for it.

### To run the playbook we just hit the terminal and write:

``` ansible-playbook -i inventories/hosts.yml playbooks/service.yml ```