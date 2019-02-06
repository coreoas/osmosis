# Osmosis

Package to keep folders synchronised between a docker container and its host.


TODO:

* Status command:
    * List containers with correct image (todo: change the image)
    * List unisons on associated ports
    * Return couples and if they are OK or not
* Start command:
    * check & create volume
    * check & start container (todo: other port, and inject SRC, EXCLUSIONS, UID, GID)
    * check & start unison and detach the process
* Stop command: stop container is enough
* Restart command:
    * stop command
    * start command
* Clean command:
    * stop command
    * remove volume
