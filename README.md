# ansible_aci
Three tier application in ACI dcloud lab. It will create Tenant, BD, 3 EPGs and contracts between them.

1) Schedule Cisco ACI 4.1 Automation v1 Lab in dcloud

2) Jump to scenario 2 and do tasks 5-9.

3) Switch to root user
```
sudo -i
```

> **Tip**: password:user01
4) chnage the working directory to user01 home directory
```
cd /home/user01
```

5) clone current repo
```
git clone https://github.com/fissil/ansible_aci.git
```

6) Execute playbook
```
ansible-playbook -e @credentials.yaml ./three_tier.yml
```

After the execution finishes walk the customer through ACI
