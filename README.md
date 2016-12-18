# hubot-responder

## What is hubot-responder?

This module takes advantage of the built in express module in hubot to provide a couple of simple web pages where your users can add simple query/responses to hubot without doing any code. The purpose is simply to allow end-users to add *simple* responses, nothing with advanced logic. Additionally, there is a global whitelist/blacklist so that you can exclude/include these responses only where you want them. This way you can allow funny responses and memes to work in channels that make sense, and ensure they don't pop into channels designated for specific purposes.

## Requirements

You will need to install hubot with a brain so that the entries you place in it are persistent. To date I've simply been using hubot-mongodb-brain, though any should work.

## Additional Details

Once this module is installed and running, visit http://yourhubotaddress:8080/setup to initialize the settings. Visiting this page again will reset everything to defaults. This will be adjusted in a future date to no longer be necessary.

Once initialized, visit: http://yourhubotaddress:8080/list to view a list of current responses. You can also add and modify existing responses.

## Installation

Clone this repo into your hubot/node_modules directory. Be sure to run an npm install after doing this so that any required modules are downloaded. You will then need to add "hubot-responder" to your external-scripts.json file in order to enable it.
