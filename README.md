Role Name
=========

Update specified python module on the remote machine through nexus or with the `.whl` file.

Requirements
------------

- python
- pip
- Nexus

Role Variables
--------------

| Var          | Description                       | Default                           |
| ------------ | --------------------------------- | --------------------------------- |
| inah_module  | Name of the python module         | inah_module_to_update             |
| nexus_url    | Nexus URL                         | nexus.domain.com/repository/repo/ |
| username     | Nexus username                    | change_me                         |
| password     | Nexus password                    | change_me                         |
| pip_version  | Pip executable to use             | pip3.11                           |
| build_folder | Relative path to the build folder | dist                              |

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
