# Week 3 — Day 2 (Monday): Permissions, Resource Usage, Packages, systemd, Logs, Users

> Videos covered: 9–16

---

## Lab 1 — Understand and modify file permissions

Create three files in your `practice` directory. Set a different permission combination on each one. Check who can read, write, or execute each file.

**Write down:** the commands used, the permission output, and an explanation of what each permission means.

---

## Lab 2 — Check system resource usage

Investigate what is currently running on your VM. Find out how much CPU and memory is being used, which processes are consuming the most resources, and how much disk space is available.

**Write down:** the commands used and interpret the output — what is using the most resources and why?

---

## Lab 3 — Install and remove a package

Using the package manager, install a tool of your choice, confirm it is installed and working, then remove it cleanly.

**Write down:** the commands used for each step and the output confirming the package was installed and then removed.

---

## Lab 4 — Manage a systemd service

Pick any installed service (e.g. `ssh` or `nginx`). Check its status, stop it, start it again, and check the status once more. Then find out how to make a service start automatically on boot and apply it.

**Write down:** every command and what changed in the status output between each step.

---

## Lab 5 — View and filter logs

Look at the system logs on your VM. Find the logs for a service you started or stopped during this session. Filter the output to show only the last 20 lines, then filter again to show only lines containing a specific keyword.

**Write down:** the commands used and paste the relevant log output.

---

## Lab 6 — Create and manage a user

Create a new user on the system, set a password for them, and add them to the sudo group. Switch to that user and confirm they have sudo access. Then delete the user.

**Write down:** every command and the output at each step.

---

## Reflection

Answer these questions in your notes:
- What does `rwxr-xr--` mean in terms of who can do what?
- What is the difference between `apt install` and downloading a binary manually?
- What is the role of `systemd` on a Linux system?
- What is the difference between `chmod` and `chown`?
- Why is it a bad practice to run everything as the `root` user?
- What does it mean for a process to be a zombie process? How would you find one?
- What is the difference between `kill` and `kill -9`? When would you use each?
- What is a package repository and why does it matter where your packages come from?
- What is the difference between `systemctl stop` and `systemctl disable`?
- What does it mean when a log shows a service "failed to start"? Where would you look to diagnose it?
- What is the difference between `su` and `sudo`? Which is safer and why?
- Why should you avoid giving a user sudo access with no password restriction in a production environment?
