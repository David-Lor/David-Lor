These are some of the main ideas I'm/I've been working on:

### 💫Main project

[VigoBus-TelegramBot](https://github.com/David-Lor/VigoBus-TelegramBot): A Telegram Bot to check the buses by stops on my hometown.
Split into 3 services ([bot backend](https://github.com/David-Lor/VigoBus-TelegramBot), [bus+stops API](https://github.com/David-Lor/Python_VigoBusAPI), [persistence API](https://github.com/David-Lor/Telegram-BusBot-DataManager)),
could be easily ported to other cities or even other public transport systems that work on a similar manner.
Deployed at [@vigobusbot](https://telegram.me/vigobusbot) (stable) and [@vigobustestbot](https://telegram.me/vigobustestbot) (development).

### ⚙️Libraries

- [Pnytter](https://github.com/David-Lor/pnytter): Python library for scraping Twitter through Nitter.
- [python-wait4it](https://github.com/David-Lor/python-wait4it): wait for a TCP port to be reachable, or a function to pass without exceptions.
- [python-pvpc](https://github.com/David-Lor/python-pvpc): wrapper for the Esios PVPC API (Spanish electricity cost).
- [ThisPersonDoesNotExistAPI](https://github.com/David-Lor/ThisPersonDoesNotExistAPI): Python interface to acquire pictures from thispersondoesnotexist.com.

### 🔀Node-RED Nodes

- [public-ip-address](https://github.com/David-Lor/node-red-contrib-public-ip-address): get the current public IP address.
- [duckdns](https://github.com/David-Lor/node-red-contrib-duckdns): update DDNS domains on DuckDNS.

### 🐳Docker images

- [Python-Git-App](https://github.com/David-Lor/Docker-Python-Git-App): image for deploying generic Python apps, that clones a repository and pip installs requirements when the container starts for the first time (from [deprecated project](https://github.com/David-Lor/Docker-Python-Autoclonable-App)).
- [SSH-PortForward-Client](https://github.com/David-Lor/Docker-SSH-Port-Forward-Client): dockerized SSH client for SSH Port Forwarding.
- [SSH-PortForward-Server](https://github.com/David-Lor/Docker-SSH-Port-Forward-Server): dockerized SSH server for SSH Port Forwarding.
- [PortForward](https://github.com/David-Lor/Docker-PortForward): TCP port forwarding in container using socat; allows forwarding multiple ports on the same container.
- (no)VNC GUI images, based on [jlesage/docker-baseimage-gui](https://github.com/jlesage/docker-baseimage-gui):
    - [FileManagers](https://github.com/David-Lor/Docker-FileManagers-GUI), with multiple file managers dockerized (Nautilus, Thunar, Dolphin)
    - [Signal Desktop app](https://github.com/David-Lor/Docker-Signal-Desktop-GUI), for the Signal messaging desktop app

### 🚉Services

- [ping2mqtt](https://github.com/David-Lor/ping2mqtt): ping multiple hosts and send ping results to MQTT topics

### 🤖Telegram bots

- [VigoBusBot](https://github.com/David-Lor/VigoBus-TelegramBot): bot for checking the remaining arrival time of buses by stops on Vigo (Galicia)
- [DalleMiniBot](https://github.com/David-Lor/dalle-mini-telegram-bot): bot interface for getting AI-generated images from DALL·E mini, directly into Telegram

### ▶️GitHub Actions

- [Tag on PR merge](https://github.com/David-Lor/action-tag-on-pr-merge): create a new tag when a Pull Request is merged
- [DockerHub: Get Tag metadata](https://github.com/David-Lor/action-dockerhub-get-tag-metadata): fetch metadata from a Docker image:tag from DockerHub

### 🧪Proof of Concepts and experimental projects

- [TwitterScraper](https://github.com/David-Lor/twitterscraper): Twitter profile scraper, microservice-based using AMQP queues, using Nitter
- [Telegram Bot Updates Receiver Service](https://github.com/David-Lor/TelegramBot-Webhook-Updates-Receiver-Service): microservice-based that receives Telegram Bot updates via Webhook, and publishes them on a queue or message broker.
- [autonice](https://github.com/David-Lor/autonice): utility for setting nice in running applications based on settings
- [pytelegrambotapi + Redis queue](https://github.com/David-Lor/pytelegrambotapi-redisqueue_POC): microservice-based Telegram Bot that uses a Redis queue to enqueue client updates, and process them with multiple workers.
- [Logging Requests](https://github.com/David-Lor/Logging-Requests-POC): API that traces log records per-requests, using Loguru + context variables, to store the records grouped by each individual request.
- [ZeroHealthCheck](https://github.com/David-Lor/ZeroHealthCheck): decentralized service that healthchecks other nodes, using ZeroMQ.
- [pydantic-etcd](https://github.com/David-Lor/pydantic-etcd): modified Pydantic BaseSettings class that supports loading variables from ETCD.

### 🗣Talks & sample projects

- [FastAPI+Pydantic+SQLAlchemy API (Pet Shelter sample)](https://github.com/David-Lor/FastAPI-Pydantic-SQLAlchemy-PetShelter-API): REST API with CRUD operations, built in Python with FastAPI, Pydantic and SQLAlchemy, simulating a fictional Pet Shelter administration system.
- [FastAPI+Pydantic+Mongo API (sample)](https://github.com/David-Lor/FastAPI-Pydantic-Mongo_Sample_CRUD_API): REST API with CRUD operations, built in Python with FastAPI, Pydantic and MongoDB.
- [pytest (examples)](https://github.com/David-Lor/pytest-talk-examples): introduction to pyTest and some of its capabilities, through examples.
- [FastAPI (lightning talk)](https://github.com/David-Lor/FastAPI_LightningTalk-Notebook): introduction to FastAPI.
- [Pydantic BaseSettings (lightning talk)](https://github.com/David-Lor/Pydantic-BaseSettings-lightning-talk): introduction to Pydantic's BaseSettings.
- [Loguru+Context (lightning talk)](https://github.com/David-Lor/Loguru-Context-examples-lightning-talk): usage of Loguru and context variables for logging.

### 🚘GTA/🐎RDR Scripts

- SimpleGangWar scripts: simple battle creator between two teams (allies and enemies) that fight each other on a frontal clash. Intended to have a nice balance between simplicity and high customization. Available for:
    - [Grand Theft Auto V](https://github.com/David-Lor/GTAV-SimpleGangWar)
    - [Grand Theft Auto IV](https://github.com/David-Lor/GTAIV-SimpleGangWar)
    - [Red Dead Redemption 2](https://github.com/David-Lor/RDR2-SimpleGangWar)
- [GTAV-LocationalDamage](https://github.com/David-Lor/LocationalDamage): implementation of a realistic damage system that reduces armor or health based on where the damage is dealt (torso or other parts).
- [GTAV-SelectiveFire](https://github.com/David-Lor/SelectiveFire): implementation of a selective fire mode for automatic guns (semi-auto and burst fire, plus full-auto).
- [GTAV-AccuracyFix](https://github.com/David-Lor/AccuracyFix): override of accuracy levels for all peds, with multiple settings.

### 🧸Scripts & others

- [Github-Actions-PR-Tag-Release](https://github.com/David-Lor/Github-Actions-PR-Tag-Release): sample repository featuring Github Actions workflows that, on a merged Pull Request including a "Tags x.y.z" line in its body, automatically creates a tag with the given version on the merge commit, and triggers a workflow for creating a new Release.
- [Spotify-Collaborative-Public-Playlists-Template](https://github.com/David-Lor/Spotify-Collaborative-Public-Playlists-Template): project to manage public Spotify playlists from Github, using Github Actions. The repository is a template that can be used to manage a playlist (one per repo).
    - [Hurdy Gurdy Rock/Metal playlist](https://github.com/David-Lor/HurdyGurdy-Rock-Metal-Spotify-Playlist): playlist with many rock/metal songs that include a hurdy gurdy
- [MQTT2NotifySend](https://github.com/David-Lor/MQTT2NotifySend): bash script that shows notifications in Linux desktops using notify-send, from messages received through MQTT
- [PVPC](https://github.com/David-Lor/pvpc): PVPC costs per day (Spanish electricity cost), powered by Github Actions and daily updated.

### 📖Articles

- [Identifying FastAPI requests in logs](https://davidlor.medium.com/identifying-fastapi-requests-in-logs-bac3284a6aa)
