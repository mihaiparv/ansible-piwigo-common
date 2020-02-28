ansible-piwigo-common
========

Ansible role which installs [Piwigo](http://piwigo.org/), a photo galery application.


Role Variables
--------------

The variables that can be passed to this role and a brief description about
them are as follows.

    # The version of the application to install
    piwigo_version: '2.7.0beta2'

    # The install directory of the application
    piwigo_install_dir: '/opt'

    # The webserver service name
    piwigo_webserver_daemon: 'apache2'

    # The webserver runtime user
    piwigo_webserver_user: 'www-data'

    # The webserver lister port
    piwigo_webserver_listen_port: '80'

    # The webserver document root directory
    piwigo_webserver_root_dir: '/var/www'

    # The contex the application will be available in `http://example.com/photos`. 
    # Piwigo can be installed at the website root, the `photos` directory is not 
    # mandatory. Whatever directory name is chosen, it is recommended to avoid 
    # showing Piwigo release number.
    piwigo_webserver_context: 'photos'

Example Playbook
-------------------------


Dependencies
------------

None

License
-------

BSD

Author Information
------------------

Parv Mihai