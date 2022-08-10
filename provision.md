1. vm VERSION="20.04.4 LTS (Focal Fossa)
2. create user for deploy (sudo group, bash console) with sudo nopassw permission
3. ssh pub key upload
4. add "hippy-server.my" ip address to /etc/hosts where playbook runs
5. for using docker plugins install next thing: ansible-galaxy collection install community.dockers