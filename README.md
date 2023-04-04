# Telegram-Message-Generator-Bot

A wrapper of [Message-Generator-DSL](https://github.com/Dirakon/Message-Generator-DSL), which uses it to post a set of scheduled randomly-generated messages into a specific chat.


## Description

Input for a message generator is inside a file `in.txt`. Rules and syntax for the message generator are better described [here](https://github.com/Dirakon/Message-Generator-DSL). This message is scheduled into a specific Telegram chat via tdlib.

## Getting Started

### Dependencies

* [npm](https://github.com/npm/cli)
* [purescript](https://www.purescript.org/)
* [spago](https://github.com/purescript/spago)

### Installing

* Run `download_dsl.sh` to prepare the message generator subproject
* Run `setup_td.sh` to prepare the message generator subproject
* Run `npm i` to install the dependencies

### Executing program

* Create or reconfigure `.env` in the format of `.env.example`
* Setup the message to be created in `in.txt`
* Run `npm run dev` to run

## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.

