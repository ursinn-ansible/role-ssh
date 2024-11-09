# Ansible Role: SSH

[![GitHub last commit](https://img.shields.io/github/last-commit/ursinn-ansible/role-ssh?logo=github&style=for-the-badge)](https://github.com/ursinn-ansible/role-ssh/commits)
[![License](https://img.shields.io/github/license/ursinn-ansible/role-ssh?style=for-the-badge)](https://github.com/ursinn-ansible/role-ssh/blob/main/LICENSE)

## Options

| Option | Default Value |
| ---- | ---- |
| role_ssh_port | 22 |
| role_ssh_users | {} |
| role_ssh_x11forwarding | no |
| role_ssh_service_name | ssh |
| role_ssh_service_state | started |
| role_ssh_service_enabled | true |
| role_ssh_service_restart_handler_state | restarted |
| role_ssh_allowed_users | [] |
| role_ssh_allowed_groups | [] |
| role_ssh_sudoers_passwordless | [] |
| role_ssh_sudoers_passworded | [] |
| role_ssh_key_types | [ed25519] |
| role_ssh_key_types_list | [ed25519, rsa, ecdsa, dsa] |
| role_ssh_key_algorithmus | [ssh-ed25519-cert-v01@openssh.com, ssh-ed25519, ecdsa-sha2-nistp521-cert-v01@openssh.com, ecdsa-sha2-nistp384-cert-v01@openssh.com, ecdsa-sha2-nistp256-cert-v01@openssh.com] |
| role_ssh_kex_algorithmus | [curve25519-sha256@libssh.org, diffie-hellman-group-exchange-sha256] |
| role_ssh_macs | [hmac-sha2-512-etm@openssh.com, hmac-sha2-256-etm@openssh.com, hmac-sha2-512] |
| role_ssh_ciphers | [chacha20-poly1305@openssh.com, aes256-gcm@openssh.com, aes256-ctr] |

## License

This project is under the MIT License. See the [LICENSE](https://github.com/ursinn-ansible/role-ssh/blob/main/LICENSE) file for the full license text.
