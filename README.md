These are some of the main ideas I'm/I've been working on:

### 💫Main project

[VigoBus-TelegramBot](https://github.com/David-Lor/VigoBus-TelegramBot): A Telegram Bot to check the buses by stops on my hometown.
Split into 3 services ([bot backend](https://github.com/David-Lor/VigoBus-TelegramBot), [bus+stops API](https://github.com/David-Lor/Python_VigoBusAPI), [persistence API](https://github.com/David-Lor/Telegram-BusBot-DataManager)),
could be easily ported to other cities or even other public transport systems that work on a similar manner. 
Deployed at [@vigobusbot](https://telegram.me/vigobusbot) (stable) and [@vigobustestbot](https://telegram.me/vigobustestbot) (development).

### 🧪Proof of Concepts

- [ZeroHealthCheck](https://github.com/David-Lor/ZeroHealthCheck): decentralized service that healthchecks other nodes, using ZeroMQ.
- [InventoryAPI](https://github.com/David-Lor/Arango-Foxx-Inventory-API): REST API to store generic items hierarchically or container-based, using ArangoDB and built as an Arango's Foxx service.
- [pydantic-etcd](https://github.com/David-Lor/pydantic-etcd): modified Pydantic BaseSettings class that supports loading variables from ETCD.
- [Logging Requests](https://github.com/David-Lor/Logging-Requests-POC): API that traces log records per-requests, using Loguru + context variables, to store the records grouped by each individual request.

### ⚙️Libraries

- [python-wait4it](https://github.com/David-Lor/python-wait4it): wait for a TCP port to be reachable, or a function to pass without exceptions
- [ThisPersonDoesNotExistAPI](https://github.com/David-Lor/ThisPersonDoesNotExistAPI): Python interface to acquire pictures from thispersondoesnotexist.com.

### 🐳Docker images

- [Python-Git-App](https://github.com/David-Lor/Docker-Python-Git-App): image for deploying generic Python apps, that clones a repository and pip installs requirements when the container starts for the first time.
- [SSH-PortForward](https://github.com/David-Lor/Docker-SSH-Port-Forward-Client): dockerized SSH client for ssh-port-forwarding.

### 🗣Talks & sample projects

- [pytest (examples)](https://github.com/David-Lor/pytest-talk-examples): introduction to pyTest and some of its capabilities, through examples.
- [FastAPI (lightning talk)](https://github.com/David-Lor/FastAPI_LightningTalk-Notebook): introduction to FastAPI.
- [Pydantic BaseSettings (lightning talk)](https://github.com/David-Lor/Pydantic-BaseSettings-lightning-talk): introduction to Pydantic's BaseSettings.
- [FastAPI+Pydantic+Mongo API (sample)](https://github.com/David-Lor/FastAPI-Pydantic-Mongo_Sample_CRUD_API): REST API with CRUD operations, built in Python with FastAPI, Pydantic and MongoDB.
- [Loguru+Context (lightning talk)](https://github.com/David-Lor/Loguru-Context-examples-lightning-talk): usage of Loguru and context variables for logging.
