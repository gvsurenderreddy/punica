Punica
======

Punica, a lightweight VPN based multi reverse proxy for NAT HTTP hosting.

Introduction
------------

Punica is a service being installed on an internet server **(Pivot Server)**.

By registering domains **(Domain)** pointing to this server, we can get a vpn account **(Account)**.

So you can serve a http service on you local machine **(Client Server)**, binding a virtual host on that domain, then connect the *Pivot Server* with the *Account*, all http traffics to the *Pivot Server* will then reverse proxy to the *Client Server*.

With *Punica*, you can easily serve your local machine on the internet, then the debugging work will be more convenient.


