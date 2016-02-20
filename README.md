# revenger playbook

ansible playbook for [revenger](https://revenger.in)

## ping

```
ansible -i hosts revenger.in -m ping
```

## execute

### production

```
ansible-playbook site.yml -i production --ask-vault-pass
```

### staging

```
ansible-playbook site.yml -i staging --ask-vault-pass
```
