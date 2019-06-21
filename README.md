hmpps-delius-core-pwm-bootstrap
=========

Bootstrap Ansible role to setup the delius-core pwm password management server


Role Variables
--------------

```yaml
region:             AWS Region
environment_name:   Environment eg. delius-core-dev
project_name:       Project eg. delius-core
ldap_protocol:      ldap or ldaps
ldap_host:          LDAP hostname
ldap_port:          LDAP port
ldap_bind_user:     LDAP admin username
ldap_bind_password: LDAP admin password
user_base:          Base root for users eg. ou=Users,dc=example,dc=com
site_url:           Front-end load balancer URL
config_location:    Where the PWM configuration file is stored eg. /usr/share/pwm
config_password:    Password required to edit the configuration through the GUI
security_key:       Security key used for encrypting tokens etc
```

License
-------

MIT

Author Information
------------------

HMPPS Digital Studio
