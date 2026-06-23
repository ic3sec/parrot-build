# parrot-build
ParrotOS HTB Ansible Build Files

# Instructions
- Start with Parrot HTB Edition (https://www.parrotsec.org/download/)
- Install pipx (apt-get install pipx)
- Install ansible (apt-get install ansible)
- Clone repo (git clone)
- Run Ansible requirement instalation (ansible-galaxy install -r requirements.yml)
- Ensure session has a sudo token
- Run Ansible playbook (ansible-playbook main.yml -K)
  - Run with --tags "[tags]" or --skip-tags "[tags]" to run specific roles

# Changelog
## 04.19.2024
- Parrot Build repo created
- Initial partial configs added to repo

## 06.23.2026
- Add tags for main playbook roles (tmux, terminal, tools)
- Add apt installation for:
  - curl
  - exiftool
  - pipx
  - xfreerdp (freerdp2-x11)
