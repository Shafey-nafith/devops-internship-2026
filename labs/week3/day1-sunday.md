# Week 3 — Day 1 (Sunday): Intro, VM Setup, Filesystem, File Editing, Bash Config

> Videos covered: 1–8

---

## Lab 1 — Set up your Virtual Machine

Following video 3, create a local Ubuntu VM using VirtualBox. Once installed and booted, log in and confirm you have a working terminal.

**Write down:** your VM specs (RAM, disk, OS version) and the command to check them.

---

## Lab 2 — Navigate the filesystem

Explore the Linux filesystem from the root `/` directory. List the contents of at least 5 important directories and write a one-line description of what each one is for.

**Write down:** the commands you used and what you found in each directory.

---

## Lab 3 — Create and edit files

Create a new directory called `practice` in your home directory. Inside it, create a text file and write a few lines into it using a terminal text editor. Then rename the file and move it to a different location.

**Write down:** every command you used and the output at each step.

---

## Lab 4 — Customize your bash environment

Add at least two custom aliases to your bash configuration file — one for a long command you would use often, and one of your choice. Reload the configuration without restarting the terminal and confirm the aliases work.

**Write down:** the aliases you added, the command to reload the config, and the output confirming they work.

---

## Reflection

Answer these questions in your notes:
- What is the difference between an absolute and a relative path?
- Where does bash look for your aliases and configuration on startup?
- What does the `~` symbol represent?
- What is the difference between a VM and a container? Which is heavier on resources and why?
- What happens when you run a command in the terminal — how does the shell find and execute it?
- What is the purpose of the `/etc` directory versus the `/var` directory?
- What is the difference between `cp` and `mv`? What happens to the original file in each case?
- Why would you use a terminal text editor like `vim` or `nano` instead of a GUI editor on a server?
- What is the difference between `.bashrc` and `.bash_profile`? When is each one loaded?
- If you create an alias in your current terminal session without saving it to the config file, what happens to it when you close the terminal?
