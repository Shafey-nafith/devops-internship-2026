# Week 3 — Day 2 (Monday): TCP/UDP, Proxies, Load Balancer, SSL

> Videos covered: 6–11

Make sure your VM is running before starting. See [setup.md](./setup.md).

---

## Lab 1 — Observe TCP vs UDP connections

On your VM, use the appropriate tools to list all active TCP and UDP connections. Then make an HTTP request in another terminal and watch a new TCP connection appear.

**Write down:** the commands you used and what you observed.

---

## Lab 2 — Set up a reverse proxy with Nginx

On your VM, run a simple backend server on a local port, then configure Nginx to act as a reverse proxy in front of it. Verify that requests to port 80 are forwarded to your backend.

**Write down:** the Nginx config you used, the commands to apply it, and the output confirming it works.

---

## Reflection

Answer these questions in your notes:
- What is the difference between a proxy and a reverse proxy?
- When would you use a load balancer instead of a reverse proxy?
- What does SSL termination mean and why is it useful?
