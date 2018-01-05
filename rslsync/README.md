docker service create --mode global --mount type=bind,source=/data/rslsync,destination=/data -e MY_SECRET=AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA --name rslsync jmcarbo/rslsync.armhf
