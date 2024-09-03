# DevSecOps

Docker ->  docker engine uses unix sockets (docker.sock) to comunicate with host OS unless we execute command on a remote host. Unix socktes use filesystem permissions, so we need to be a member of docker group or be root to run docker commands.. //run "groups" cmd 

