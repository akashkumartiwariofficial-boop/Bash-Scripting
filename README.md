# Bash-Scripting
Write a Bash script to read the contents of a protected file (secret.txt) from the TryHackMe Room.

# TryHackMe - Bash Scripting Assignment

## 📋 Objective
The goal of this assignment is to write a Bash script that reads the contents of a protected file (`secret.txt`), stores it in a variable, and prints it onto the terminal screen.

---

## 🚀 Steps & Implementation

### 1. Connect to the Target Machine
* Open the [TryHackMe Room](https://tryhackme.com/jr/tutedude-cybersec) and establish an SSH connection to the target machine as outlined in the course instructions.

### 2. Create and Edit the Script
Create a script file named `read_secret.sh` using any text editor (such as `nano` or `vi`) and add the following code:

```bash
#!/bin/bash

# Read the contents of secret.txt and store it in a variable
secret_content=$(cat secret.txt)

# Print the value of the variable on the screen
echo "$secret_content"

