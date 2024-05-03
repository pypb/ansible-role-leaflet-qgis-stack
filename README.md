# Ansible Role: leaflet-qgis-stack

Sets up a web map stack using these components:

- traefik reverse proxy
- varnish http accelerator
- nginx serving leaflet
- mapproxy
- qgis-server

## Requirements

Requires docker and docker compose. Podman will probably work too, but has not been tested.

You will also require a QGS project file with a map and configure mapproxy to request WMS layers from qgis-server, otherwise this will be a very boring software stack.

## License

Apache License Version 2.0

## Author Information

[https://github.com/pypb](https://github.com/pypb "github.com/pypb")
