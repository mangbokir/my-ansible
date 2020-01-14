# my-ansible

Mangbokir ansible structure

├── platforms
│   └── < Vagrantfile >
│
└── provisioning
    ├── <ansible.cfg>
    ├── playbook
    ├── inventories
    |   ├── hostsvars
    │   ├── Environment prod
    │   │   └── group_vars
    │   └── Environment vagrant
    │       └── group_vars
    └── roles
        └── <specific roles>
