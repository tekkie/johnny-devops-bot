# Johnny DevOps

The bot that interprets your DevOps team commands and executes them.

## Install

First grab the source and its dependencies.

```bash
$ git clone git@github.com:tekkie/johnny-devops-bot.git
$ cd johnny-devops-bot
$ npm install
```

## Configure

Copy the environment file.

```bash
$ cp .env.sample .env
```

and adjust its contents to match your values.
During development we use `DEBUG=true` to work with the `ConsoleConnector`.

## Execute

In development mode, simply start Johnny with:

```bash
$ node app.js
```
