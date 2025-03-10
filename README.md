Lighthouse role
=========

Deploy Lighthouse to host

Requirements
------------
Centos 7

Role Variables & default values
--------------

- `lighthouse_address` - address for your machine
- `lighthouse_install_dir` - directory to download and unarchive lighthouse package
- `nginx_config_path` - local nginx config path
- `nginx_config_file` - *DO NOT CHANE* path to save nginx config
- `nginx_package` - name of nginx package
- `nginx_port` - port to access lighthouse

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| `lighthouse_address` | EMPTY | address for your machine |
| `lighthouse_install_dir` | /opt/lighthouse | directory to download and unarchive lighthouse package |
| `nginx_config_path` | template/lighthouse.conf | local nginx config path |
| `nginx_config_file` | /etc/nginx/conf.d/light.conf | *DO NOT CHANE* path to save nginx config |
| `nginx_package` | nginx.x86_64 | name of nginx package |
| `nginx_port` | 45454 | port to access lighthouse |


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - src: git@github.com:DaddyMorlan/lighthouse-role.git
    scm: git
    version: "1.0"
    name: lighthouse 

License
-------

Morlan

Author Information
------------------

DaddyMorlan
