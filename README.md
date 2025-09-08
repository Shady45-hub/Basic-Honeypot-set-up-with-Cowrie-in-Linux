# Basic-Honeypot-set-up-with-Cowrie-in-Linux
Honeypots help you study attacker behavior. And this setup mimics SSH/Telnet.

# Cowrie Honeypot Lab

## Introduction
This project demonstrates the setup of a basic honeypot using [Cowrie](https://github.com/cowrie/cowrie) on Kali Linux.  
The goal is to simulate vulnerable SSH and Telnet services, allow attackers to log in with weak credentials, and capture their activities for analysis.

## Objectives
- Deploy a Cowrie honeypot on Kali Linux.  
- Configure weak credentials to allow attacker login.  
- Test both SSH and Telnet access locally.  
- Analyze attacker logs and interactions.  

## Setup Steps

### 1. Clone and Install Cowrie

# clone cowrie repository
git clone https://github.com/cowrie/cowrie.git
cd cowrie

# create Python virtual environment
python3 -m venv cowrie-env
source cowrie-env/bin/activate

# install requirements
pip install --upgrade pip
pip install -r requirements.txt
