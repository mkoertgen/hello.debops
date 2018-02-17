# hello.debops

Trying out [debops/debops](https://hub.docker.com/r/debops/debops/).

## Getting started

Create your first debops environment

```bash
$ docker-compose run debops
Creating network "hellodebops_default" with the default driver
ansible@1b510051b85b:~$ debops-init ~/src/projects/my-environment
Creating new DebOps project directory in /home/ansible/src/projects/my-environment ...
ansible@1b510051b85b:~$
```

## Run all playbooks for project `my-environment`

```bash
$ docker-compose run debops
Creating network "hellodebops_default" with the default driver
ansible@925955b2cf46:~$ cd src/projects/my-environment/
ansible@925955b2cf46:~/src/projects/my-environment$ debops
Running Ansible playbook from:
/home/ansible/.local/share/debops/debops/ansible/playbooks/site.yml ...
...
```
