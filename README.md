# Video-Game-Recommendation-Bot

Link: https://discord.com/oauth2/authorize?client_id=1235006287797026946

The objective of this project was to create a video game recommendation engine that utilizes data obtained from steam’s API upon request from the user through discord.
The retrieved data is then passed to ChatGPT’s api where it analyzes relevant data to generate a recommendation.
In the current iteration of the project, recommendations are generated based on the steam library associated with a user.
From there the game genres are collated based on the library obtained. Based on the most common genre, ChatGPT generates its recommendation.

--VGRB is not currently hosted, if you want to use the bot you must run the existing code

Testing Discord Bot:

1. Install/download all necessary tools as shown below
2. Join current Discord Server or add to existing Discord Server
   - If joining our current Discord server use the link: https://discord.gg/rqadz9uj
4. Use the link provided to add the bot to existing server: https://discord.com/oauth2/authorize?client_id=1235006287797026946&permissions=0&scope=bot
5. Clone repository
6. Run the code, go to bot.py and run the python file, this will put the Video Game Recommendation Bot online in the server
7. While in the Discord server with the recommendation bot online, type the !recommend command in the chat bar to start recommendation process per recommendation, use !help for help
8. Next type in a Steam user account name, this is indicated by the last section of your https link in the top section of your steam account
           ie. https://steamcommunity.com/id/BlueJay819/ -> BlueJay819
9. End the script to return Video Game Recommendation Bot offline

DOWNLOADS:

Discord
- https://discord.com/download

Steam
- https://store.steampowered.com/about/

Python
- https://www.python.org/downloads/

INSTALLATIONS:

discord.py
- pip install discord.py
- https://pypi.org/project/discord.py/

python-steam-api
- pip install python-steam-api
- https://pypi.org/project/python-steam-api/

beautifulsoup4
- pip install beautifulsoup4
- https://pypi.org/project/beautifulsoup4/

openai
- pip install --upgrade openai
- https://platform.openai.com/docs/quickstart?context=python
