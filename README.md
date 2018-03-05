# Deploying a MongoDB cluster with Ansible

- Tested with Ansible 2.4
- Expects CentOS/RHEL 7 hosts

Comandos variados:

- rs.status()
- rs.printSlaveReplicationInfo()
- cfg.members[0].votes = 1;
- cfg.members[0].priority = 1;
- /opt/rh/rh-mongodb34/root/bin/mongoimport --db test --collection trades --drop --file trades.json
