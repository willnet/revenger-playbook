# revenger playbook

ansible playbook for [revenger](https://revenger.in)

## ping

```
ansible -i hosts revenger.in -m ping
```

## execute

### production

```
ansible-playbook -i hosts revenger.yml --ask-vault-pass
```

### staging

```
ansible-playbook -i staging-hosts revenger-staging.yml --ask-vault-pass
```
