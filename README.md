# Rasa + Rocket.Chat

This repository is a simple bot made to solve the [Rasa](https://rasa.com) + [Rocket.Chat](https://rocket.chat/) integration bug.

## Usage

## Installation

### Rasa

* In your **virtualenv** install RASA:

```sh
pip install -r requirements.txt
```

### Rocket.Chat

* Simply up the Rocket.Chat container:

```sh
docker-compose up -d
```

* Access the local Rocket.Chat instance at [http://localhost:3000/home](http://localhost:3000/home).

* It is needed to create the user **bot** with the same data on `credentials.yml`


## References

* [Rasa with Rocketchat documentation](https://rasa.com/docs/rasa/user-guide/connectors/rocketchat/)

* [Rocket.Chat.py.SDK](https://github.com/RocketChat/Rocket.Chat.py.SDK/tree/develop)

* [run-rocketchat.py](https://github.com/lappis-unb/tais/blob/master/bot/run-rocketchat.py)

* [rocketchat_API](https://github.com/jadolg/rocketchat_API)
