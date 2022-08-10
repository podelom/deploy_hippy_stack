# deploy_hippy_stack

if run playebook on mac m1:<br>
export OBJC_DISABLE_INITIALIZE_FORK_SAFETY=YES <br>

ansible-playbook -i environments playbooks/{{appropriate_playbook}}.yaml <br>
OR <br>
ansible-playbook -i environments playbooks/master.yaml <br>


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

Grafana dashboards:
Cadvisor exporter: 14282
node-exporter-full: 1860