# vanilla-node-blizzard-oauth-example

Example node.js web application using express http framework and node-fetch to consume the Blizzard OAuth API using the Authorization Code flow to access a users account data, without any other frameworks or OAuth libraries.

## Getting Started

1. Clone this repository.
2. Copy the `.env.example` file to a file named `.env`.
3. Fill in the `CLIENT_ID` and `CLIENT_SECRET` values with the values you retrieve from develop.battle.net.
4. Run `npm run dev` in your terminal.
5. Visit `http://localhost:3000/login` in your browser to start the auth flow.