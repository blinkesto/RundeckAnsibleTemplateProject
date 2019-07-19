# RundeckAnsibleTemplateProject

Create properties/PROJECT_NAME.yaml with:


```yaml
name: testproj2
git_url: https://github.com/blinkesto/TestProject1.git
```

Run

```bash
ansible-playbook createproject.playbook --extra-vars "prop=properties/PROJECT_NAME.yaml"
```
