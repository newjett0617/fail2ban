# fail2ban

copy config to mount container
```
cp sshd/jail.d/sshd.conf data/jail.d/
```

reload fail2ban config
```
docker-compose exec fail2ban fail2ban-client reload
```

ref from https://github.com/crazy-max/docker-fail2ban
