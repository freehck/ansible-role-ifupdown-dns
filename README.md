ifupdown-dns
=========

Role ifupdown-dns configures network/interfaces and update resolvconf configuration.

Example
----------------

    - role: ifupdown-dns
      iface_name: enp0s17
      iface_type: inet
      iface_nameserver: 8.8.8.8
      iface_domain: mydomain.ru
