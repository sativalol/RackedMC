# rack

basic minecraft server panel.

## features
- manage files, upload, edit, rename, delete
- live terminal stream, send commands
- start/stop/kill server via screen
- live metrics (cpu/ram)
- discord oauth whitelist login

## setup
1. clone it
2. `npm i`
3. copy `config.example.json` to `config.json` (setup your allowed discord IDs and mc directory path)
4. set env variables (`.env`):
   ```
   DISCORD_CLIENT_ID=...
   DISCORD_CLIENT_SECRET=...
   DISCORD_REDIRECT_URI=http://localhost:3000/auth/callback
   SESSION_SECRET=some-random-string
   ```
5. `npm start`
