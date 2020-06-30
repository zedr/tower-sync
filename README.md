```
ansible-playbook -l tower update-workflow.yaml -e tower_user=admin -e tower_password=letmein -e git_repo_uri=ssh://git@github.com/zedr/ansible-playbook-samples.git -e tower_host=tower.local -e workflow_id=10
```
