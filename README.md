# ansible-letsencrypt
## Usage
1. git clone https://github.com/ThienBao96/ansible-letsencrypt.git
2. cd ansible-letsencrypt
3. Create your own website in folder ./build
4. Edit in hosts.yaml: 
  - ansible_ssh_host: {HOST_IP}
  - ansible_ssh_user: {HOST_USER_NAME}
  - ansible_ssh_private_key_file: {PATH_TO_SSH_KEY}
  - letsencrypt_email: {YOUR_EMAIL}
  - domain_name: {DOMAIN_NAME}
 5. Run: ansible-playbook playbook.yml -i hosts.yaml
