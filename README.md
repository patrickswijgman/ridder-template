# Game

## Getting started

Install dependencies

```shell
npm ci
```

Run the game

```shell
npm start
```

## Adding assets to the game

Place your textures, sounds, fonts and any other assets for your game in the `public` folder. Refer to them without the `public` prefix in your code.

```javascript
// load 'public/textures/player.png' like so:
const texture = loadTexture("textures/player.png");
```

## Build for a website

```shell
npm run build
```

And upload the files from the `dist` directory to your web server.
