# Development Laptop Setup with Xfce4

This Ansible playbook is designed to configure a development laptop with Xfce4.

## Install Python requirements

Before running the playbook, ensure you have the required Python packages
installed. You can do this by running:

```bash
uv pip install -U -r requirements.txt
```

## Run the Playbook

To execute the playbook, use the following command:

```bash
ansible-playbook -i inventory -K playbook.yml
```
