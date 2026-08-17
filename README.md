# hp_omen_max_16_playbook

Ansible playbook for configuring HP Omen Max 16 on Fedora Linux.

## Overview

Automated system configuration for HP Omen Max 16 laptop running Fedora. Includes hardware optimization, driver setup, and development environment configuration.

## Features

- Hardware-specific optimizations
- GPU driver setup (NVIDIA/AMD)
- Development tools installation
- LLM/local AI setup
- System tuning

## Usage

```bash
# Install dependencies
sudo dnf install ansible

# Run playbook
ansible-playbook -i inventory.ini style.yml

# LLM setup (optional)
ansible-playbook -i inventory.ini llm_setup.yml
```

## Structure

```
├── inventory.ini     # Host configuration
├── style.yml        # System config
├── llm_setup.yml    # Local LLM setup
└── resources/       # Additional configs
```

## Requirements

- Fedora Linux
- Ansible 2.9+
- HP Omen Max 16 (recommended)

## License

MIT
