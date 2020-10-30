- [Role Name](#Role-Name)
- [Requirements](#Requirements)
- [Role Variables](#Role-Variables)
- [Dependencies](#Dependencies)

Role Name
=========
## gke

A brief description of the role goes here.

Requirements
------------
The GCP modules require both the requests and the google-auth libraries to be installed.
install pip for RHEL / CentOS
``` 
$ sudo yum install python-pip3 
```
``` 
$ pip3 install requests google-auth 
```

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------
To work with the GCP modules, you’ll first need to get some credentials in the JSON format:

#### [Create a Service Account](https://developers.google.com/identity/protocols/oauth2/service-account#creatinganaccount)
#### [Download JSON credentials](https://support.google.com/cloud/answer/6158849?hl=en&ref_topic=6262490#serviceaccounts)


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
