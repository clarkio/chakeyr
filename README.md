# chakeyra
A live streaming game where the streamer and viewers in chat compete to typing challenges

Thanks to @timothee for the name of this game 😆🙏

## Clarkio
This game was built with 💙 live on stream with the programming community. Come and hang out with us over on Twitch!

> https://twitch.tv/clarkio


### Prerequisites

- Node.js: [nvm](https://github.com/nvm-sh/nvm) or [nvm-windows](https://github.com/coreybutler/nvm-windows)

### Update/create your .env file

In the root of the repo, you'll see an example [.env.example](.env.example) file, copy this, and create a `.env` file

Fill in the following fields in your new `.env` file:

- TWITCH_CLIENT_ID
- TWITCH_CLIENT_SECRET
- TWITCH_CHANNEL_ID

### Getting Started (traditional)

1. Open your terminal/command line tool
1. Run `npm install`
1. Run `npm start`
1. Open your browser to [http://localhost:3000/](http://localhost:3000/)

### Getting Started (Docker)
1. Open your terminal/command line tool
1. Run `docker-compose up`
1. Open your browser to [http://localhost:3000/](http://localhost:3000/)

### Playing the Game

1. Click "Start"
1. You (the streamer) will receive a set of words and can begin typing them out character by character
1. Your chat will receive a smaller set of words and once they send single character messages to your chat room it will validate them again their separate words
1. The first to complete every character wins
