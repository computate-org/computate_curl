
# Install the curl ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_curl

# Clone the curl ansible role. 
git clone git@github.com:computate-org/computate_curl.git ~/.ansible/roles/computate.computate_curl

# Change into the curl ansible role directory. 
cd ~/.ansible/roles/computate.computate_curl
```

# Run the curl ansible playbook to install curl locally. 

```bash
ansible-playbook install.yml
```

Christopher Tate
