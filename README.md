# Cloudera manager 5 with embedded Postgres.

## Deployment.
You need to have ansible installed on your deployment agent.

1. Clone the code from this repository. 
2. Replace `ansible_ssh_host: 10.111.4.50` in `host_vars/cloudera_manager.yml` 
   with your host.
3. Run `ansible-playbook -i nodes  provision.yml`
