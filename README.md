# ansible-logscale

This set of playbooks is designed setup a limited logscale deployment for legacy architectures without k8s

```bash
sudo dnf install ansible
ansible-galaxy install -r requirements.yml

ansible all -a true --ssh-extra-args="-o UpdateHostKeys=yes -o StrictHostKeyChecking=accept-new" -i inventory/pslab.yml


```
