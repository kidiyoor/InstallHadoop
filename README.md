# InstallHadoop
Install Hadoop:pseudo-distributed mode using Ansible playbook

sudo apt-get install ansible OR pip install ansible

ssh-keygen -t rsa //not required

sudo ansible-playbook hadoop14.yml -i "localhost," -c local //Install hadoop locally
