<p align="center">
  <img src="images/Untitled_design__19_-removebg-preview.png" alt="GameNet logo" width="150">
</p>

# GameNet

a website that hosts a bunch of unblocked browser games in one place, 100% ad-free. built as a bigger project after making a few small games individually and wanting somewhere to actually put them.

live at [gamenet-zeta.vercel.app](https://gamenet-zeta.vercel.app)

## what's in it

a landing page that leads into a dashboard of games, plus a few extra pages for tracking what you've played and favorited.

games included:

- 2048
- flappy bird
- pong
- tic tac toe
- stick game

## pages

- `home.html` - landing page with the intro and play button
- `index.html` / `dash.html` - main dashboard where you pick a game
- `favorite.html` - your favorited games
- `played.html` - games you've recently played
- `original.html` - extra page, older version of the dashboard

each game has its own html file plus a matching css and, where needed, js file for game logic (flappybird.js, pong.js, tic.js, stick.js).

## how it's built

plain html, css, and javascript, no frameworks. each game is self-contained in its own set of files so they're easy to add to or swap out. deployed on vercel.

## running it locally

clone the repo and open `home.html` in a browser, or serve the folder with any static file server. no build step needed.
