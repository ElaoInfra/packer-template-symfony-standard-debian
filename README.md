# Symfony Standard - Debian #

62Go ext4, 2Go swap

 * Debian 7.9 - amd64
   * Openssh-server
   * Nfs support (nfs-common, cachefilesd)
   * VirtualBox - Guest Additions 5.0.10 (dkms, linux-headers)
   * Ansible 1.9.4 (python-pycurl)
   * Vim 7.4 (backports)
   * Git 1.9.1 (backports)
   * Oh-my-zsh
   * Make 3.81
   * Acl

 * Curl 7.26.0
 * Ruby 2.2.1p85 (bearstech)
 * Gem 2.4.5 (bearstech)
 * Python 2.7.3
 * Pip 7.1.2
 * Node 0.12.7 (nodesource)
 * Npm 2.11.3 (nodesource)
 * Php 5.6.13 (dotdeb)
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
 * Bower 1.5.2
 * Gulp 3.9.0
 * Php cs fixer ???
 * Php CS ???

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

## Changelog ##

### 1.0.4

* No longer add vagrant public ssh key to docker build
* Disable splash screen during preseed
* Use google dns servers
* Use debian httpredir as apt sources
* Fix oh-my-zsh user configuration file group permission
* No more annoying mouse support in vim
* Default locale to C.UTF-8
* Ansible as a debian package
* Acl support
* php-cs-fixer
* phpcs
