google searches
---------------
ansible ping server
ansible all collections
ansible inventory commands
ansible install package
ansible install package dnf
ansible start service


ansible command module
Ansible register output
ansible condition
ansible vars from arguments

ansible filters
ansible convert string to int
ansible loops 
ansible mysql module, mysql_info, mysql_db
ansible pip

ansible command vs shell --> google search and intw qn
ansible add user
ansible create directory
ansible download file
ansible args chdir
ansible copy module
ansible service daemon-reload
ansible service
ansible remove file
ansible unzip
ansible dnf
aws increade vcpu limit

ansible roles
ansible config
How to unset environment variable in linux
ansible templates
ansible handlers
ansible import role
ansible vault

Interview Qns/Notes: 
--------------

- Share ur screen and write ansible playbook and install nginx and ping module.
- What is Adhoc command in Ansible -- It is ansible command line to run modules against nodes, instead of playbooks. for some urgency purposes.
- What is playbook: playbook is a yaml file containing list of modules or collections. we can write any number of plays in a single play book. also we can target localhost. where ansible is running thats the localhost. 
- Ansible means not only connecting to remote servers, it can connect to local softwares like ec2, azure, aws, gcp any popular software in the world.
- debug module is just like echo in linux.


pip --> this is for installing python dependencies

- How can u handle errors in ansible?
- ansible command vs shell
- what modules did u use in ansible

when u run a command and to take that output into a variable we should be using register: variable_name

What is Ansible Role? intw qn
Role is a proper structure of variables, tasks, templates, handlers etc Using Roles we can reuse the code

what are handlers in ansible? intw qn
Handlers are nothing but notifiers in ansible..when there is change in config we can notify some task to restart server.
to restart like nginx only when there is change in configuration like expense.conf.j2 then we use notifiers
notify:
- restart nginx

ansible-vault create credentials.yaml
ansible-vault view credentials.yaml
ansible-vault edit credentials.yaml