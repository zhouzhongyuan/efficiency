# Efficiency

## Modify hosts
```bash
gedit /etc/hosts
```

## Start replaced server
```bash
sudo /home/y/.npm-global/bin/http-server -p 80
```
- Because `/home/y/.npm-global/bin` only exists in `y` user, not `root` user. 
- To use the `80`(all ports less than 1024 exactly) port, we must use as `root` user.