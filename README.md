# igx-orin-playbook

## Run this:

Install deps

```
ansible-galaxy collection install -r requirements.yml
```

```
ansible-playbook -b -K -e vnc_password=YOURPASSWD -i YOURSSHHOST, deploy-igx-orin.yml
```

_DONT FORGET THE COMMAN in YOURSSHHOST_
