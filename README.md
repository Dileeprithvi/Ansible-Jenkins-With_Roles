# Ansible-Jenkins-With_Roles

Installation of Open Source Jenkins with Ansible Playbook using Ansible Roles

Ansible Roles:

- Roles provide a framework for fully independent, or interdependent collections of variables, tasks, files, templates, and modules.
- Each role is basically limited to a particular functionality or desired output, with all the necessary steps to provide that result either within that role itself or in other roles listed as dependencies.
- Roles are not playbooks. Roles are small functionality which can be independently used but have to be used within playbooks.
    
    
Ansible Galaxy: Command line tool for installing, creating and managing roles.   

How to create Ansible roles using Ansible Galaxy command : ansible-galaxy init <name of the role>
                                              Example    : ansible-galaxy init jenkins
                                              
The ansible galaxy command creates the 8 directories and  8 files respectively.

tree <Name of the Role>
tree jenkins
.
├── defaults
│   └── main.yml
├── files
├── handlers
│   └── main.yml
├── meta
│   └── main.yml
├── tasks
│   ├── jenkins.yml
│   └── main.yml
├── templates
├── tests
│   ├── inventory
│   └── test.yml
└── vars
    └── main.yml
    
    
Ansible Modules Used: - yum - get_url - rpm_key - systemd - wait_for: timeou - shell - debug    
    

    
    
    
