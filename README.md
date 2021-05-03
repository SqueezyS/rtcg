# RTCG

RTCG, or Replit Trading Card Game is a community project for making a card index out of the ReplTalk population. This repository contains the source for both the card API and the Design framework the cards in a webpage enviornment.

### Structure

Each portion of the project exists in it's own folder. These projects are repls hosted on repl that you can view from [`here`](https://replit.com/@rtcg).

### License and Credits

RTCG Team: `frissyn`, `Dart`, and `miro`

All source code for RTCG is under an **MIT License**.

## Documentation

Documentation written by SqueezyS

#### ./cards [GET]
https://api.rtcg.repl.co/cards

Returns a JSON formatted string. Used for grabbing all the cards when you load up the game or app

#### ./card/<iden> [GET]
https://api.rtcg.repl.co/cards/69420

<iden> is an integer, it is used to grab the card by id. (possibly) returns a json formatted string for that card

### Private

#### ./card/add [POST]

You have to have a token in order for this to actually work. Assuming you do, you have to put in the name, image, title, rarity, color, and if it's a shiny (bool) to actually work. Will return a 201 if it adds succesfully, else, it will return a 403

