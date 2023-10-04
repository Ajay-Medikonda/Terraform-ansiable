#Ansible Topics
0. Enable call backs in ansible.cfg 
   [defaults]
   callbacks_enabled = timer, profile_tasks, profile_roles
   #The above provided playbook and task execution time which can allow us to identiy slow running playbooks.

1.Adhoc commands
2. with_items for running iterations.
3. when condition
4. return code using rc
5. Ansible facts using Redis.
6. Copy, File, No_Log, Debug
7. Verbosity using -vvvv
8. Notify & Handlers
9. ignore_errors: true
10. block, rescue & always
11. Vault Encrypt String and File for aws_creds
12. shell & command modules
13. become_user
14. get_url and unarchive modules in redis playbook.
15. serial option select how many machine can run at a time. serial 1 will run  
    on   one machine only.
16. lineinfile
17. Docker Swarm Configuration
18. Set-fact
19. --extra-vars ansible_user='ubuntu' 
20. fetch
21. tags
22. Jinja Templates
23. Pre & Post Tasks
24. Roles and Ansible Galaxy
25. Dynamic Inventory
26. AWX
$Env:AWS_ACCESS_KEY_ID="XX"
$Env:AWS_SECRET_ACCESS_KEY="XXX"
$Env:AWS_REGION="us-east-1"


Good article to speedup playbook execution:
https://www.redhat.com/sysadmin/faster-ansible-playbook-execution


