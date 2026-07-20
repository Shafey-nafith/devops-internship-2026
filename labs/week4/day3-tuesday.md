# Week 3 — Day 3 (Tuesday): SSL/TLS, NAT, DNS, How the Browser Works

> Videos covered: 12–16

Make sure your VM is running before starting. See [setup.md](./setup.md).

---

## Lab 1 — Inspect an SSL/TLS certificate

Use `openssl` to connect to a website and read its SSL certificate. Look for the issuer, subject, validity dates, and Subject Alternative Names (SANs).

**Write down:** the command you used and what you found in the certificate.

---

## Lab 2 — Trace DNS resolution step by step

Use `dig` with the trace option to follow a domain name from the root DNS servers all the way to its final answer. Also query different record types (A, MX, NS).

**Write down:** the commands you used and which DNS servers were queried at each step.

---

## Lab 3 — Trace a browser request using curl

Use `curl` in verbose mode to simulate what a browser does when visiting a page. Observe the DNS lookup, TCP handshake, TLS handshake, and HTTP response in the output.

**Write down:** the command you used and a summary of each phase you observed.

---

