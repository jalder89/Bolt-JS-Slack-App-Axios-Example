# Bolt-JS-Slack-App-Axios-Example
A simple example of a Slack App using Bolt JS SDK and Axios to receive a message, get some sample data, and return it as a formatted message.

You will need to follow the getting started guide to setup a Slack App here: https://slack.dev/bolt-js/tutorial/getting-started-http

You will want to listen to messages, so subscribe to the same bot events mentioned here: https://slack.dev/bolt-js/tutorial/getting-started-http#setting-up-events-with-http

How you host your app is up to you, locally via ngrok, remotely via Heroku, your choice. You'll need to provide your Slack App with the URL for your app, wherever it is hosted.When setting up your Slack App's Events Request URL, keep in mind that bolt listens for events on `/slack/events`. For example, this is the Forwarding URL when working with ngrok. So when using ngrok your Events Request URL for your Slack App would be: `https://{ngrok-forwarding-URL}/slack/events`

Remember to setup your environment variables, this example uses `dotenv` package to pull variables from a `.env` file. If you're not familiar with `dotenv` you can find the Github repo and documentation here: https://github.com/motdotla/dotenv.

You won't need any of the app code from the guide as the example already includes the code you need. You can easily expand upon the code as you see fit, there is some great example code on the SDK documentation here: https://slack.dev/bolt-js/concepts#basic

You can find further documentation on Axios here: https://axios-http.com/docs/intro
