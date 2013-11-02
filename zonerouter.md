---
id: zonerouter
tags: #go, WIP
title: zonerouter
---

A highly available, fast, distributed solution for service discovery and configuration.

[zonerouter](https://github.com/tav/zonerouter) will offer:

- better consensus protocol than Raft, Paxos, etc.
- based around ticks
- fast messaging over udp, using nacl for authentication and integrity
- redis-esque simple persistence format
- super-high throughput