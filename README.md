# Notepad
## Clear logs of docker container
```sh
echo "" > $(docker inspect --format='{{.LogPath}}' <container_name_or_id>)
```
