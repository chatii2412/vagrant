# vagrant

Configure `Vagrantfile` by using a yaml file.

## Prerequisites

* [Vagrant](https://www.vagrantup.com/)
* [VirtualBox](https://www.virtualbox.org/) (This `Vagrantfile` currently only supports VirtualBox.)
* [SSH Keys](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/#generating-a-new-ssh-key)

## Quick Start

```bash
$ cp config-example.yaml config.yaml
$ cp docker-compose-example.yaml docker-compose.yaml
$ vagrant plugin install vagrant-docker-compose
$ vagrant up
```
