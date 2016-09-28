Repo Info
=========
A [Docker] container to load-balance DNS services on `TCP/UDP`..

Requirements
------------
Define your [Docker] service group-name when spinning up.

```
docker run -d -p 53:53 -p 53:53/udp \
  -e BACKEND_SERVICE_NAME="dns-servers" \
  mrlesmithjr/nginx-lb:ubuntu-dns-lb
```

License
-------

BSD

Author Information
------------------

Larry Smith Jr.
- [@mrlesmithjr]
- [everythingshouldbevirtual.com]
- [mrlesmithjr@gmail.com]

[Alpine]: <https://alpinelinux.org/>
[Ansible]: <https://www.ansible.com/>
[DNSMasq]: <http://www.thekelleys.org.uk/dnsmasq/doc.html>
[Docker]: <https://www.docker.com>
[@mrlesmithjr]: <https://twitter.com/mrlesmithjr>
[everythingshouldbevirtual.com]: <http://everythingshouldbevirtual.com>
[mrlesmithjr@gmail.com]: <mailto:mrlesmithjr@gmail.com>