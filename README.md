# Backup User with Least Privilege (Linux)

##  Description 
This project demonstrates how to create a restricted Linux user for backups
using the **Least Privilege** principle.

The 'backup' user is allowed to run **only '/bin/tar' with sudo**
and nothing else.

---

##  User setup
- User: 'backup'
- Shell: '/bin/bash'
- Home: '/var/backups'

---

## Sudo restriction 
Only this command is allowed: 

'''bash
sudo /bin/tar
 All other sudo commands are denied.


