# Week 3 — Lab Setup: Local Virtual Machine

Before starting any lab this week, set up a local Linux VM on your machine. This VM will be your lab environment for all three days.

---

## Step 1 — Install VirtualBox

Download and install VirtualBox from the official site: https://www.virtualbox.org/wiki/Downloads

Choose the installer for your operating system (Windows, macOS, or Linux) and follow the installation wizard.

---

## Step 2 — Download Ubuntu Server

Download the Ubuntu Server 22.04 LTS ISO from: https://ubuntu.com/download/server

This is the operating system you will install inside the VM.

---

## Step 3 — Create the Virtual Machine

Open VirtualBox and create a new VM with the following settings:

- **Name:** lab-week3
- **Type:** Linux
- **Version:** Ubuntu (64-bit)
- **RAM:** 2048 MB (2 GB) minimum
- **Disk:** 20 GB, dynamically allocated

Attach the Ubuntu ISO you downloaded as the boot disk.

---

## Step 4 — Install Ubuntu Server

Start the VM and follow the Ubuntu Server installation wizard:

- Choose your language and keyboard layout
- Use the default storage configuration (entire disk)
- Set a username and a password you will remember
- When asked about OpenSSH, **enable it** — you will need SSH access for the labs
- Wait for the installation to complete, then reboot

---

## Step 5 — Configure the Network

Before starting the VM, go to its network settings in VirtualBox and change the adapter from **NAT** to **Bridged Adapter**. This gives the VM its own IP address on your local network so you can SSH into it from your host machine.

Start the VM, log in, and find the VM's IP address. Write it down — you will use it in every lab.

---

## Step 6 — Update the System

After logging in, update all system packages to make sure everything is up to date.

**Write down:** the commands you used to update the system and confirm it completed successfully.

---

## Step 7 — Connect via SSH from your Host

From your host machine (not inside the VM window), open a terminal and SSH into the VM using the IP address you noted. Confirm the connection works before moving on to the labs.

**Write down:** the command you used and the output confirming you are connected.

---

Once all steps are done and you can SSH into the VM from your host, you are ready to start [Day 1](./day1-sunday.md).
