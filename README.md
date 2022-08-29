# Configure Jenkins with Ansible
This repository contains Ansible code that automatically configures Docker engine and Jenkins on top of it.

## How to Install Ansible
### Create a Python virtual environment
1. Open terminal.
1. Clone this repo.
    ```
    git clone git@github.com:hiriumi/ansible-jenkins.git
    ```
1. CD into the directory
    ```
    cd ansible-jenkins
    ```
1. Create a virtual environment.
    ```
    python3 -m venv venv
    ```
1. Activate it.
    ```
    source ./venv/bin/activate
    ```

### Install Ansible
1. Install Ansible. This will take a while.
    ```
    pip install ansible
    ```

