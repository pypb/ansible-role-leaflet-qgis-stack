# Ansible Role: leaflet-qgis-stack

Set up a web map stack using Leaflet, MapProxy and QGIS Server with Traefik reverse-proxy and Varnish cache.

## Requirements

Requires docker and docker compose. Podman will probably work too, but has not been tested.

You will also need:
 - A QGS project file with a map for QGIS Server
 - MapProxy configuration to request layers using WMS from QGIS Server
 - Optionally a seeding configuration for MapProxy

## License

Apache License Version 2.0

## Author Information

[https://github.com/pypb](https://github.com/pypb "github.com/pypb")
