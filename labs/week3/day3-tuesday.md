# Week 3 — Day 3 (Tuesday): Streams, Variables, find, SSH, scp, rsync

> Videos covered: 17–24

---

## Lab 1 — Work with streams and output redirection

Run a command that produces output and redirect its standard output to a file. Then redirect its error output to a separate file. Finally, combine both into one file.

**Write down:** the commands used and the contents of each output file.

---

## Lab 2 — Use variables in bash

Create at least three shell variables — one for your name, one for a directory path, and one of your choice. Use them in commands and print their values. Then make one of them persist across terminal sessions.

**Write down:** how you defined each variable, how you used it, and how you made it persistent.

---

## Lab 3 — Search with the find command

Use the `find` command to:
- Find all files in `/etc` modified in the last 7 days
- Find all files in your home directory larger than 1 MB
- Find all directories named `log` on the system

**Write down:** the exact commands and the results returned.

---

## Lab 4 — Transfer files using scp and rsync

Between your host machine and your VM (or between two directories on the VM), transfer a file using `scp`. Then transfer a directory using `rsync`. Run `rsync` a second time without changing anything and observe what happens.

**Write down:** the commands used, the output of each transfer, and what was different about the second `rsync` run.

---

## Lab 5 — Remote management with SSH

Generate an SSH key pair on your host machine and copy the public key to your VM so you can log in without a password. Confirm it works.

**Write down:** every step, the commands used, and the output confirming passwordless login works.

---

## Reflection

Answer these questions in your notes:
- What is the difference between `stdin`, `stdout`, and `stderr`? Give a real example of each.
- What does `2>&1` do and when would you use it?
- What is the difference between a local variable and an environment variable in bash?
- Why do environment variables matter in DevOps? Give an example of where they are commonly used.
- What is the difference between `find` and `grep`? When would you use one over the other?
- What does `find . -type f -name "*.log" -mtime +30` do in plain English?
- What is the difference between `scp` and `rsync`? When would you prefer one over the other?
- Why does `rsync` not re-transfer files that haven't changed? How does it know?
- What is the difference between a public key and a private key in SSH? Which one do you share?
- What happens if someone gets access to your private SSH key?
- Why is passwordless SSH login considered more secure than password-based login?
- What is the risk of leaving an SSH port open to the public internet?

---

