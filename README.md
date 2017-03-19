Rancher CLI and Rancher Compose CLI in one container
====================================================

In my continuous delivery pipeline I needed the combination of Rancher and Rancher Compose without having two jobs and a race condition.
I merged the monostream/rancher and monostream/rancher-compose configurations to get a container with the two Rancher CLI tools.

Sources:
* https://github.com/monostream/docker-rancher-compose
* https://github.com/monostream/docker-rancher-cli
