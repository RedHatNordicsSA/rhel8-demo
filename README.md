# rhel8-demo
Demonstration of RHEL8 capabilities

# Howto
1. Clone this repo
```
git clone https://github.com/RedHatNordicsSA/rhel8-demo
```

2. Edit inventory and fill in the IP of your demo host
```
cd rhel8-demo
vi inventory
```

3. Edit the rhsm role with your RHSM user/pass
```
vi roles/rhsm/tasks/main.yml
```

4. Run demo playbook
```
ansible-playbook ./hosts demo.yml -u root
```

