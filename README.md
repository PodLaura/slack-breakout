# slack-breakout
Slack bot to facilitate creating breakout sessions from team channels

## Local Development
1. Save the bot token and Signing Secret as environment variables.
These can be found on the app setup page within https://api.slack.com/apps.
    
Copy your Signing Secret from the Basic Information page and then store it in a new environment variable. 
    
The following example works on Linux and macOS; but similar commands are available on Windows.
    
`export SLACK_SIGNING_SECRET=<your-signing-secret>`
    
Copy your bot (xoxb) token from the OAuth & Permissions page and store it in another environment variable.
    
`export SLACK_BOT_TOKEN=xoxb-<your-bot-token>`
    
2. Install node packages `npm install`


3. Run application `node app.js`

The application will run on port 3000 by default

4. Install / configure a proxy to forward events to your local application. For example https://ngrok.com/docs/getting-started 