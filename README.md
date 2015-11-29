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
   * Make 3.81
   * Acl

 * Curl 7.26.0
 * Ruby 2.2.1p85 (bearstech)
 * Gem 2.4.5 (bearstech)
 * Python 2.7.3
 * Pip 7.1.2
 * Node 0.12.8 (nodesource)
 * Npm 2.14.9 (nodesource)
 * Php 5.6.15-1 (dotdeb)
   * php5-common, php5-cli, php5-fpm
   * php5-readline, php5-intl, php5-curl
   * php5-xdebug
 * Composer 1.0-dev
 * Nginx 1.8.0 (dotdeb)
 * Mailcatcher 0.6.1
 * PhantomJS 1.9.8
 * Supervisor 3.1.3
 * Log.io
 * Capifony 2.8.6
 * Bower 1.6.8
 * Gulp 3.9.0
 * PHP CS Fixer 1.10.2
 * PHP_CodeSniffer 2.4.0

## Miscellaneous ##

 * Vagrant integration (user & public ssh key)
 * Vim customization (default editor, syntax highlighting, ...)
 * Increase git performance over nfs with *core.preloadindex true*

 * Ssh customization (Reverse dns lookup, disable locale environment)
 * Supervisor web server enabled on port 9001
 * Mailcatcher web server on port 1080
 * PhantomJS webdriver enabled on port 4444
 * Oh-my-zsh theme & plugins
 * SYNFONY_ENV environment variable set to "dev"

## Todo

 * Remove git repo "packer-templates"
 * Switch from phantomjs to electron (http://electron.atom.io/)
 * Fix php acl permissions
 * Mailcatcher as a package (systemd + don't use ruby/pthon roles anymore)
 * Supervisor as a package (systemd + don't use ruby/pthon roles anymore)
 * Forgive capifony (ansible based deployment)
 * Switch from logio to heka/rtail)
 * Php 7
