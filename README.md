Ansible playbook which is made for deploying docker role for inventory group [app] depending on os distribution
and deploying postgres role for inventory group [db] with ability to customize postgres version and data folder location (can be defined in inventory)

ansible defaults is defined in ansible.cfg

#RUNNING PLAYBOOK:

cd ~/ansible
  
ansible-playbook -i hosts playbook/main.yml
