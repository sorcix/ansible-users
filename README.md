# Ansible `users` role

## Configuration

This role expects a `users` dict with the following structure:

```
users:
  username:
    id: 1000 # optional user id
    group: "test" # optional primary group
	 shell: "/bin/bash" # optional login shell
	 password: "..." # optional encrypted password
	 sudo: true # whether or no to give this user root access through sudo
```
