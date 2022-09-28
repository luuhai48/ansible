# HOW TO USE ANSIBLE

## Install Ansible
Using `pip`:
```bash
python3 -m pip install --user ansible
```

On ubuntu:
```bash
sudp apt install ansible
```

On MacOs:
```bash
brew install ansible
```

## Create `inventory.ini` file

```ini
[servers]
your-server-config-host-name # Edit ~/.ssh/config
root@192.168.1.11 # Your ssh connection to server

[servers:vars]
username=
password=
```

## Alter `play.yml`

## Run
```bash
ansiple-playbook play.yml
```
