# LoRa Picocell Gateway and packet forwarder from Semtech for Docker Compose
This project is meant to be run on a Linux host.

Based on the following repository:
- [Connectitude/lora-pico-gw-forwarder](https://github.com/Connectitude/lora-pico-gw-forwarder)
## Getting started
Prerequisites:
- Docker
- Docker Compose

Run the following commands:

    git clone https://github.com/earsnot/picogw.git
    cd picogw/

Go into /data/global_conf.json and set "gateway_conf.server_address" to the desired address.
Open the docker-compose.yml file and change the ports to the desired ports.\
Run the following command:

    sudo docker-compose up

The gateway ID is being echoed to the terminal during initialization and should be added to ChirpStack (or whatever you use) as a gateway.
