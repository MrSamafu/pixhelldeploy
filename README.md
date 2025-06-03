# pixhelldeploy
Deploy apipix and pixhellfestdb on server with ansible playbook

# Backlog TODO

## Ansible
- The files used by an Ansible roles should be placed under the 'files' folder of the role: [check the doc](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_reuse_roles.html) CHECK
- Find a way to manage sensible values, ex: password
    - you could use ansible-vault
    - you can also generate a random password during deployment and write in a file on the server
- Add in the readme the description of the target server supported by your deployment: OS, version, etc...
- Update the deployment to use a distant server if you can and be carefull with the management of the private key to connect


## Docker
- Fix convention name for Dockerfile, ex: Dockerfile.api -> api.Dockerfile
- Add a dev container configuration on your repo and use it to develop [check the doc](https://code.visualstudio.com/docs/devcontainers/containers)
