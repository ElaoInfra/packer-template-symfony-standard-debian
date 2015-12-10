# Symfony Standard - Debian #

62Go ext4, 2Go swap

 * Debian 8.2 - amd64
   * Openssh-server
   * Nfs support (nfs-common, cachefilesd)
   * VirtualBox - Guest Additions 5.0.10 (dkms, linux-headers)
   * Ansible 1.9.4 (python-pycurl)
   * Vim 7.4
   * Git 2.1.4
   * Oh-my-zsh
   * Make 4.0
   * Acl

 * Node 5.2.0 (nodesource)
 * Npm 3.3.12 (nodesource)
 * Php 7.0.0 (dotdeb)
   * php-common, php7.0-common, php7.0-cli, php7.0-fpm
   * php7.0-opcache, php7.0-json, php7.0-intl, php7.0-curl
 * Composer 1.0-dev
 * Nginx 1.8.0 (dotdeb)
 * MailHog 0.1.8
 * PHP CS Fixer 1.11
 * PHP_CodeSniffer 2.4.0

## Miscellaneous ##

 * Vagrant integration (user & public ssh key)
 * Vim customization (default editor, syntax highlighting, ...)
 * Increase git performance over nfs with *core.preloadindex true*

 * Ssh customization (Reverse dns lookup, disable locale environment)
 * MailHog web server on port 8025
 * Oh-my-zsh theme & plugins
 * SYNFONY_ENV environment variable set to "dev"

## Todo

 * Add php xdebug
 * Switch from phantomjs to electron (http://electron.atom.io/)
 * Fix php acl permissions
 * Supervisor as a package (systemd + don't use ruby/pthon roles anymore)
 * Forgive capifony (ansible based deployment)
 * Switch from logio to heka/rtail
