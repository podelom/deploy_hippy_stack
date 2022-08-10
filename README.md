# deploy_hippy_stack

if run playebook on mac m1:
export OBJC_DISABLE_INITIALIZE_FORK_SAFETY=YES

ansible-playbook -i environments playbooks/{{appropriate_playbook}}.yaml
OR
ansible-playbook -i environments playbooks/master.yaml


Destination resources:
```
promtail 9080
node-exporter 9100
cadvisor 9280
grafana 3000
loki 3100
prometheus 9090
alertmanager 9093
```
