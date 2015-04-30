# Puckman

Scott Pilgrim: "Did you know that the original name for Pac-Man was Puck-Man? You'd think it was because he looks like a hockey puck but it actually comes from the Japanese phrase 'Paku-Paku,' which means to flap one's mouth open and closed. They changed it because they thought Puck-Man would be too easy to vandalize, you know, like people could just scratch off the P and turn it into an F or whatever."

This is a game of Pacman, ported to SceneVR. It is based on [pacman.js by @platzhersh](https://github.com/platzhersh/pacman-canvas).

## Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

Fork this repo, then deploy to Heroku to have your own game of Puckman to play with friends.

## Technology

The map is converted to a grid of boxes (a large dark blue one and a thin light blue border). The power pulls are rendered as cubes, with `collision-response` set to false, which means that the code can detect when you run into them, but you won't bounce off them.

A large hovering billboard is updated periodically to display the scores of the players.

