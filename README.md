# Home Assistant

Here you can find my home assistant (HA) configs/automations.

## Prerequisites

- Synology NAS with `docker` installed.

## Setup

1. Pull `homeassistant/home-assistant` from the registry.

1. create config folder on NAS: `/docker/homeassistant/config`

1. copy `automations.yaml` to newly created `config` folder

1. setup a new `homeassistant` container using the `homeassistant/home-assistant` image

1. configure container to use same network as host

1. use `enable auto-restart`

1. map `/docker/homeassistant/config` to `/config`
