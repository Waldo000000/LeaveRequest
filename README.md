# SlackBotRtm
A starting point for a Slack bot based on Slack's [RTM API](https://api.slack.com/rtm).

## Install
Add a bot integration to your Slack instance:

1. [Custom Integrations](https://my.slack.com/apps/manage/custom-integrations)
2. Bots -> Add Configuration
3. Take note of the `API Token` for use at runtime below

Prepare the bot:

```
npm install
```

## Run
```
set SLACK_API_TOKEN=<API Token from installation above>&& npm start
```
