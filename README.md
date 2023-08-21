# ansible-prototype-k8s-grafana
Ansible playbook to install Grafana on Kubernetes in docker desktop


## Install

Ensure docker desktop is running with Kubernetes enabled

Run the playbook
```
ansible-playbook -i site.yml
```

Grafana can be accessed through the ingress at http://grafana.local, by adding the host entry
```
127.0.0.1   grafana.local
```

