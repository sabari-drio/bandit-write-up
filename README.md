# Bandit OverTheWire Writeup (Levels 1-20) 🚀

## Introduction 📖

The Bandit wargame from OverTheWire is a great way to learn Linux commands and basic cybersecurity concepts.  
This writeup provides solutions for levels for beginners.

## Connecting to Bandit 🔗

Each level requires an SSH connection using the provided credentials.

````bash
ssh banditX@bandit.labs.overthewire.org -p 2220
````
Replace X with the current level number and enter the retrieved password when prompted.

## Solutions ✅
## Level 0 → Level 1
Task: 📜
Retrieve the password stored in the file readme in the home directory.

Solution: 🏆
````bash
cat readme
````
Copy the displayed password and use it to log in to Level 1.
