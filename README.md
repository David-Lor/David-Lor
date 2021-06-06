These are some of the main ideas I'm/I've been working on:

### 💫Main project

[VigoBus-TelegramBot](https://github.com/David-Lor/VigoBus-TelegramBot): A Telegram Bot to check the buses by stops on my hometown.
Split into 3 services ([bot backend](https://github.com/David-Lor/VigoBus-TelegramBot), [bus+stops API](https://github.com/David-Lor/Python_VigoBusAPI), [persistence API](https://github.com/David-Lor/Telegram-BusBot-DataManager)),
could be easily ported to other cities or even other public transport systems that work on a similar manner. 
Deployed at [@vigobusbot](https://telegram.me/vigobusbot) (stable) and [@vigobustestbot](https://telegram.me/vigobustestbot) (development).

### ⚙️Libraries

- [python-wait4it](https://github.com/David-Lor/python-wait4it): wait for a TCP port to be reachable, or a function to pass without exceptions.
- [ThisPersonDoesNotExistAPI](https://github.com/David-Lor/ThisPersonDoesNotExistAPI): Python interface to acquire pictures from thispersondoesnotexist.com.

### 🔀Node-RED Nodes

- [public-ip-address](https://github.com/David-Lor/node-red-contrib-public-ip-address): get the current public IP address.
- [duckdns](https://github.com/David-Lor/node-red-contrib-duckdns): update DDNS domains on DuckDNS.

### 🐳Docker images

- [Python-Git-App](https://github.com/David-Lor/Docker-Python-Git-App): image for deploying generic Python apps, that clones a repository and pip installs requirements when the container starts for the first time (from [deprecated project](https://github.com/David-Lor/Docker-Python-Autoclonable-App)).
- [SSH-PortForward-Client](https://github.com/David-Lor/Docker-SSH-Port-Forward-Client): dockerized SSH client for SSH Port Forwarding.
- [SSH-PortForward-Server](https://github.com/David-Lor/Docker-SSH-Port-Forward-Server): dockerized SSH server for SSH Port Forwarding.

### 🚉Services

- [ping2mqtt](https://github.com/David-Lor/ping2mqtt): ping multiple hosts and send ping results to MQTT topics

### 🧪Proof of Concepts

- [Telegram Bot Updates Receiver Service](https://github.com/David-Lor/TelegramBot-Webhook-Updates-Receiver-Service): microservice-based that receives Telegram Bot updates via Webhook, and publishes them on a queue or message broker.
- [autonice](https://github.com/David-Lor/autonice): utility for setting nice in running applications based on settings
- [pytelegrambotapi + Redis queue](https://github.com/David-Lor/pytelegrambotapi-redisqueue_POC): microservice-based Telegram Bot that uses a Redis queue to enqueue client updates, and process them with multiple workers.
- [Logging Requests](https://github.com/David-Lor/Logging-Requests-POC): API that traces log records per-requests, using Loguru + context variables, to store the records grouped by each individual request.
- [ZeroHealthCheck](https://github.com/David-Lor/ZeroHealthCheck): decentralized service that healthchecks other nodes, using ZeroMQ.
- [pydantic-etcd](https://github.com/David-Lor/pydantic-etcd): modified Pydantic BaseSettings class that supports loading variables from ETCD.
- [InventoryAPI](https://github.com/David-Lor/Arango-Foxx-Inventory-API): REST API to store generic items hierarchically or container-based, using ArangoDB and built as an Arango's Foxx service.

### 🗣Talks & sample projects

- [FastAPI+Pydantic+SQLAlchemy API (Pet Shelter sample)](https://github.com/David-Lor/FastAPI-Pydantic-SQLAlchemy-PetShelter-API): REST API with CRUD operations, built in Python with FastAPI, Pydantic and SQLAlchemy, simulating a fictional Pet Shelter administration system.
- [FastAPI+Pydantic+Mongo API (sample)](https://github.com/David-Lor/FastAPI-Pydantic-Mongo_Sample_CRUD_API): REST API with CRUD operations, built in Python with FastAPI, Pydantic and MongoDB.
- [pytest (examples)](https://github.com/David-Lor/pytest-talk-examples): introduction to pyTest and some of its capabilities, through examples.
- [FastAPI (lightning talk)](https://github.com/David-Lor/FastAPI_LightningTalk-Notebook): introduction to FastAPI.
- [Pydantic BaseSettings (lightning talk)](https://github.com/David-Lor/Pydantic-BaseSettings-lightning-talk): introduction to Pydantic's BaseSettings.
- [Loguru+Context (lightning talk)](https://github.com/David-Lor/Loguru-Context-examples-lightning-talk): usage of Loguru and context variables for logging.

### 🚘GTA5/🐎RDR2 Scripts

- [GTAV-SimpleGangWar](https://github.com/David-Lor/GTAV-SimpleGangWar): simple battle creator between two teams (allies and enemies) that fight each other on a frontal clash. Intended to have a nice balance between simplicity and high customization.
- [RDR2-SimpleGangWar](https://github.com/David-Lor/RDR2-SimpleGangWar): simple battle creator between two teams (allies and enemies) that fight each other on a frontal clash. Intended to have a nice balance between simplicity and high customization.
- [GTAV-LocationalDamage](https://github.com/David-Lor/LocationalDamage): implementation of a realistic damage system that reduces armor or health based on where the damage is dealt (torso or other parts).
- [GTAV-SelectiveFire](https://github.com/David-Lor/SelectiveFire): implementation of a selective fire mode for automatic guns (semi-auto and burst fire, plus full-auto).
- [GTAV-AccuracyFix](https://github.com/David-Lor/AccuracyFix): override of accuracy levels for all peds, with multiple settings.

### 🧸Scripts & others

- [Spotify-Collaborative-Public-Playlists-Template](https://github.com/David-Lor/Spotify-Collaborative-Public-Playlists-Template): project to manage public Spotify playlists from Github, using Github Actions. The repository is a template that can be used to manage a playlist (one per repo).
    - [Hurdy Gurdy Rock/Metal playlist](https://github.com/David-Lor/HurdyGurdy-Rock-Metal-Spotify-Playlist): playlist with many rock/metal songs that include a hurdy gurdy
    - [Sample/Test playlist](https://github.com/David-Lor/Spotify-Collaborative-Public-Playlists-Test): playlist used as sample repository, and for testing new features
- [MQTT2NotifySend](https://github.com/David-Lor/MQTT2NotifySend): bash script that shows notifications in Linux desktops using notify-send, from messages received through MQTT
- [mkvmerge-zenity-scripts](https://github.com/David-Lor/mkvmerge-zenity-scripts): compilation of GUI scripts to perform simple operations on videos, running mkvmerge, and using zenity/yad for modal windows.
