# nfvpe-infrared
This is a project to Integrate Infrared with NFVPE use cases

For Intel Lab we need to sync all the repos to local storage.
For this we need VPN conection and then we need to run this playbook -
ansible-playbook playbooks/reposync.yml --extra-vars "puddle_id=2017-07-01.1"
