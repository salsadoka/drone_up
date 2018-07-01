# drone_up


1. Create ubuntu machine
1. Clone this repo onto that machine
1. Populate variables in below script & run it on your virtual machine to create a drone.env file.

```
#FILE="./drone.env"

/bin/cat <<EOM >$FILE
# Drone secret key, used for private communication between agents and web UI
DRONE_SECRET=
DRONE_GITHUB_CLIENT=
DRONE_GITHUB_SECRET=
DRONE_ADMIN=
DRONE_HOST= 
EOM
```
4. Run start_up script
