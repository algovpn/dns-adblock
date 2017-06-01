algovpn.dns-adblock
===================

Add DNS adblocking to AlgoVPN.

Role Variables
--------------

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| `adblock_lists` | ["http://winhelp2002.mvps.org/hosts.txt", "https://adaway.org/hosts.txt", "https://www.malwaredomainlist.com/hostslist/hosts.txt", "https://hosts-file.net/ad_servers.txt"] | List of adblock feeds |


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: algovpn.vpn, vpn_clients: ['client1', 'client2']}
         - { role: algovpn.dns-adlblock }

License
-------

MIT

Author Information
------------------

AlgoVPN