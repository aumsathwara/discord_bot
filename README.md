# PeerWill

A discord bot that can encourges you, greet you and track your activity. 

The scripts use discord.py library of python. The process is pretty straight forward. 

# Steps to construct your own discord bot:
	1 Go to the Discord Developer Portal (https://discord.com/developers/applications) and log in with your Discord account.

	2 Click the "New Application" button. Give your application a name and click "Create".

	3 Click the "Create a Bot" button on the right side of the page.

	4 Click the "Copy" button next to the "Token" field to copy your bot's token to your clipboard. You will need this token later to authenticate your bot with the Discord API.

	5 Click the "Copy" button next to the "Client ID" field to copy your bot's client ID to your clipboard. You will need this ID later to invite your bot to a server.

	6 Open a text editor and create a new file. This will be the main file for your Discord bot.

	7 Import the Discord.py library and use the Client class to create a new bot client. Use the run() method to start the bot using your bot's token.
	
	8 Click the "Copy" button next to the "Client ID" field to copy your bot's client ID to your clipboard. You will need this ID later to invite your bot to a server.

	9 Open a text editor and create a new file. This will be the main file for your Discord bot.

	10 Import the Discord.py library and use the Client class to create a new bot client. Use the run() method to start the bot using your bot's token.
	
		import discord

		client = discord.Client()

		@client.event
		async def on_ready():
		    print(f'{client.user} has connected to Discord!')

		client.run('YOUR_BOT_TOKEN_HERE')

	
	11 Save the file and run it using Python.If everything is set up correctly, you should see a message in the console indicating that your bot has connected to Discord.

	12 Invite your bot to a server using the OAuth2 URL generator on the Discord Developer Portal. Select the "bot" scope and copy the generated URL into your web browser to add your bot to a server.

	13 Start creating commands for your bot by using the @client.command() decorator. For example, the following code creates a command called hello that sends a message to the channel when the command is used:



# Output
Below are some functionality one can achieve using discord.py 

  ![image](https://user-images.githubusercontent.com/55092131/209943763-71ecb3d4-c5a3-4d4e-988b-5577766d0403.png)

  ![image](https://user-images.githubusercontent.com/55092131/209943862-c3530d89-6329-4ed2-9ba5-9dd9a2451538.png)

  ![image](https://user-images.githubusercontent.com/55092131/209944182-8e1c0748-7286-427d-b72a-3835e15d2a87.png)

  ![image](https://user-images.githubusercontent.com/55092131/209944344-d4411b8f-0d65-47df-a46b-7e10de94fda1.png)
