# Ansible Role for configure (debian) clients.

**summary**
This role is for configuration (debian) clients.
Look in the tasks directory for each configuration.
All configurations are held atomically via their own files. 

## Variables that have to be defined

| variable | description |
| -------- | ----------- |
| install_kde_desktop | bool install kde - main use to install kde in a conainer. So the acpi packages are maked. |
| full_ca_cert_path | 
| firefox_allowed_to_install_extensions |
| default_user | default user for the _postfix_ configuration. |

