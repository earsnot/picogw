# LoRa Picocell Gateway and packet forwarder from Semtech for Docker Compose
This project is meant to be run on a Linux host.

Based on the following repositories
- [LoRa Picocell Gateway HAL](https://github.com/Lora-net/picoGW_hal)
- [LoRa network packet forwarder](https://github.com/Lora-net/picoGW_packet_forwarder)
## Getting started
Run the following command:

    git clone https://github.dev/earsnot/picogw.git

Go into /data/global_conf.json and set "gateway_conf.server_address" to the desired address.
Open the docker-compose.yml file and change the ports to the desired ports.
Run the following commands:

    docker-compose build
    docker-compose up