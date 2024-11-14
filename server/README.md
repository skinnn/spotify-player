## Spotify Player API

#### Installation
1. Clone repo and run `npm i`
2. Create spotify app on [Spotify Developer Dahboard](https://developer.spotify.com/dashboard) with Redirect URI of the web client (in this case http://localhost:3000), and enable Web API and Web Playback SDK support
3. Create `.env.development` file with env variables for Client ID, Client secret and Redirect URI using values from the spotify app settings (*`.env` file is just an example*).
4. Run `npm start` or `npm run dev` for hot reload