puppet-defaultconfig
=============

https://github.com/example42/puppet-apache/pull/7

Usage:

    class { 
      'apache':
        source_dir => "puppet:///modules/defaultconfig/$::operatingsystem/$::operatingsystemrelease/apache",
        source_dir_purge => true
    }
