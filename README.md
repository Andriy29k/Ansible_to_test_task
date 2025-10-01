# Ansible_to_test_task
### Ansible configure and run application on host

### Pre requires
1. Determine next environment variables in Github Secrets in repository with application:

   * PRIVATE_SSH_KEY (Ssh key to Host where will be deployed app).
   * TOKEN (PAT to get access to repo with application).
   * SERVER_IP (IP address of remote machine).
   * TLS_CERT_KEY (TLS key for certificate).
   * TLS_CERT_PEM (TLS pem for certificate).
   * SSH_CONFIG (Ssh config which will be using to connect remote machine, required for inventory.ini).
   * INVENTIRY (Inventory file with settings and servers).

2. Trigger CI with appliction on dev branch via push, or trigger by hands on Github Actions. 
3. Test application.
