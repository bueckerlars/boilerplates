Vor dem Deployen muss der SMB Share gemountet werden. Dazu kann folgender Befehl genutzt werden:
```sh
sudo mount -t cifs -o username=USERNAME,password=PASSWORD,uid=1000,gid=1000 //<server>/<share> /mnt/media
```

## Setup Guide
Hier ist die [Github](https://github.com/jlesage/docker-handbrake) Repo.