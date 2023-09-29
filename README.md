# このリポジトリについて 

Ansibleを使って、Amazon Linux 2023 に GitLab CEを構築します。

## 準備

```bash
cp hosts.example hosts
vim hosts

vim group_vars/all
```

## 構築

```bash
ansible-playbook -i hosts site.yml
```
