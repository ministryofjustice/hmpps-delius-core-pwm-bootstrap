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
site_url:           Load-balancer URL
config_url:         Where the PWM configuration file is stored eg. /usr/share/pwm
```

License
-------

MIT

Author Information
------------------

HMPPS Digital Studio
