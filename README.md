# puppet-snmp module


This is the snmp module. Use this module to manage snmp clients. It will install the snmp packages 
and provides a template configuration.

## Recommended use
```
  class { 'snmp':
    syslocation => 'your location goes here',
    syscontact 	=> 'your email address goes here',
  }
```
