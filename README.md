# Smalltalk- the Rasa Demo Bot
[![Actions Status](https://github.com/donbale/smalltalk-demo/workflows/Continuous%20Integration/badge.svg?branch=master)](https://github.com/donbale/smalltalk-demo/actions)

## :surfer: Introduction
The purpose of this repo is to showcase a contextual AI assistant built with the open source Rasa framework. 

It also includes a docker-compose file for easy dev deployment.

## 👷‍ Installation

To install, please clone the repo and run:

```
cd smalltalk-demo
pip install -r requirements.txt
pip install -e .
```
This will install the bot and all of its requirements.
Note that this bot should be used with python 3.6 or 3.7.

## 🤖 To run Sara:

Use `rasa train` to train a model (this will take a significant amount of memory to train,
if you want to train it faster, try the training command with
`--augmentation 0`).

Then, to run the rasa server, action server and duckling:

docker-compose up 

## Roadmap:
- Integrate UI into docker-compose file
- Add tests 