# pixhelldeploy
Deploy apipix and pixhellfestdb on server with ansible playbook and create the databases

# Target server

This application is used on a Linux Debian server.
If you want use on an other OS its at your own risk.
I think, this app work on every linux distrubutions.

You need to have on the server:

- SSH enable
- Python 
- Port 22 open ( for ssh )
- Every port in this app, so 3306,3000 and 5173 need to be openned
- the sudo access
- password for ansible-vault (Ask to owner) --ask-vault-password
