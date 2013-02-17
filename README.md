puppet-defaultconfig
=============

example42/puppet-apache#10

Usage:

    class { 
      'apache':
        source_dir => "puppet:///modules/defaultconfig/$::operatingsystem/$::operatingsystemrelease/apache",
        source_dir_purge => true
    }
