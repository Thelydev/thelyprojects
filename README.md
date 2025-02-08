There is all my bots, i made tutorials
on https://www.youtube.com/channel/UC613DJwjAgTCzQ7jBhUyyWg.

#Simple Main.py file

import discord
from discord.ext import commands

bot = commands.Bot(command_prefix=".", intents=discord.Intents.all())

@bot.event
async def on_ready():
    print("the bot is ready!")

bot.run("YOUR-TOKEN")
