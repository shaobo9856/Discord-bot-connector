# Discord-with-flowise

This is a simple Discord bot implemented using flowise. To set it up and run, please follow the steps mentioned below:

## Pre-requisites

Ensure you have `Python` installed on your machine.

## Setup

You will need to set up environment values:

API_URL = os.environ["URL"]

headers = {"Authorization": os.environ["API_KEY"]}

my_secret = os.environ['DISCORD_BOT_SECRET']

Set env values:

1. nano ~/.bashrc
2.
   export URL="http:///api/v1/prediction/8f0c9a8"
  
   export API_KEY="EFWszbuNT00D "

   export DISCORD_BOT_SECRET="MT"
  
3. source ~/.bashrc

## After setting up the environment values, you can run the Python script by using the command:

```python
python main.py
```
Further Reading
If you are interested in creating your own Discord bot using flowise, you can check out my articles for more detailed information and guides:

[Create your own Discord bot with flowise:](https://medium.com/aimonks/how-to-create-pdf-chat-discord-bot-without-coding-skills-215e6065aae6)



docker build -t discordbot .


docker run -d discordbot


