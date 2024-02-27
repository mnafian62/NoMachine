
+ docker build -t nomachine .
+ docker run --rm -d --network host --privileged --name nomachine-xfce4 -e PASSWORD=root -e USER=root --cap-add=SYS_PTRACE --shm-size=1g nomachine
