**Structuring a YAML Playbook with Ansible

**Introduction
We've been hired as systems administrators for a company that uses Ansible for its configuration management. While we have no prior Ansible experience, we are familiar with YAML and have been assured that with nothing but our YAML knowledge and some guiding, we should be able to write a playbook, which is a file that configures one aspect of a managed system.

**Logging In
Use the credentials provided on the hands-on lab overview page, and log in as cloud_user. Ansible has already been installed on a test system, so once we're logged in we can switch to the ansible user with su - ansible. The password is the same as it is for cloud_user. Once we are ansible, we also need to forward our SSH key:

[ansible@host]$ ssh-copy-id localhost
Now we can begin.