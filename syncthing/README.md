docker service create --mode global --mount type=bind,source=/data/syncthing/data,destination=/var/syncthing --mount type=bind,source=/data/syncthing/config,destination=/var/syncthing/config --name syncthing --network host jmcarbo/syncthing.arm