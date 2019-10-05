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


## References

* [Rasa with Rocketchat documentation](https://rasa.com/docs/rasa/user-guide/connectors/rocketchat/)
