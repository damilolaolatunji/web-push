# Web Push Notifications Demo

Tutorial: https://pusher.com/tutorials/push-notifications-node-service-workers

## Getting Started

1. Clone this repository and `cd` into it.
2. Execute `npm install` to download dependencies.
3. Run `./node_modules/.bin/web-push generate-vapid-keys` to generate public/private VAPID key pair
4. Open `client/main.js` and `variables.env` and update them with your VAPID credentials
5. Run `node server.js` to start the Express server
6. Visit http://localhost:5000 in your browser.

## Prerequisites

- [Node.js](https://nodejs.org/en) and npm

## Built With

- [web-push](https://github.com/web-push-libs/web-push)

## Licence

[MIT](https://opensource.org/licenses/MIT)

