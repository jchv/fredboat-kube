# Fredboat-Kube
This repository provides a Helm chart for running Fredboat in Kubernetes.

## TODO

* Needs testing. (Currently this chart is untested, but is based heavily on manifests I have deployed. There is very likely at least a couple mistakes in this version.)

* Memory limits are weird and non-configurable, CPU limits are non-existent.

* Network policies could be tighter (specifically for DNS.)

* Currently not possible to use normal PostgreSQL/RabbitMQ charts; RabbitMQ should be easy, PostgreSQL may require some work (probably init container for schema initialization.)

* RabbitMQ/PostgreSQL authentication not configurable.

* Need more configuration options for Fredboat options.
