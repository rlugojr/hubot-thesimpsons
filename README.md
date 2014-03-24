# Hubot: hubot-simpsons

A Simpsons Quote and Image Generator for Hubots.

[![Build Status](https://travis-ci.org/jjasghar/hubot-imgur_thesimpsons.png?branch=master)](https://travis-ci.org/jjasghar/hubot-imgur_thesimpsons)


See [`src/imgur_thesimpsons.coffee`](src/imgur_thesimpsons.coffee) for full documentation.

## Installation

Add **hubot-imgur_thesimpsons** to your `package.json` file:

## Installation

Add **hubot-simpsons** to your `package.json` file:
>>>>>>> omar/master

```json
"dependencies": {
  "hubot": ">= 2.5.1",
  "hubot-scripts": ">= 2.4.2",
  "hubot-imgur_thesimpsons": ">= 0.0.0"
}
```

Add **hubot-imgur_thesimpsons** to your `external-scripts.json`:

```json
["hubot-imgur_thesimpsons"]
```

Run `npm install hubot-imgur_thesimpsons`

Add **hubot-simpsons** to your `external-scripts.json`:

```json
["hubot-simpsons"]
```

## Sample Interaction

```
user1>> hubot simpsons quote
hubot>> "Good thing I drink plenty of… malk?"
```
user1>> hubot simpsons image
hubot>> http://i.imgur.com/mKzawbN.png
```
