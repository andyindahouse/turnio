# Turnio

a Slack bot to manage a queue of slack users in a channel.

## Why?

Sometimes it's necesary to create a queue for differents things in the day-to-day.

## How?

Turnio expose a API with main functionalities of a queue. You only need to mention him with some of next commands:

`add`   >   Add a user to the queue
`del`   >   Delete user of the queue
`show`  >   Show the queue 
`clean` >   Delete all users in the queue 
`help`  >   Show the turnioAPI avalaible 

### Install

Clone this repository:

`git clone https://github.com/andyindahouse/turnio.git`

Install dependencies, including [Botkit](https://github.com/howdyai/botkit):

```
cd turnio
npm install
```

Get a Slack bot token [from your Slack team](https://my.slack.com/apps/new/A0F7YS25R-bots)

Run your bot from the command line with your new tokens:

`token=<slack token> node .`

Invite @turnio to your slack-channel 

(in Slack channel) `/invite @turnio`

## More info

This bot was build with [Botkit Studio Starter Kit](https://github.com/howdyai/botkit-studio-starter) 


