# Discord-Python-Rol-Verme

Önce yukarıdaki ayarları yapın. 
Yoksa bot hiçbir şekilde çalışmayacaktır.

Python dosyası okutmadıysanız hiç CTLR+" (konsol tuşu TAB'ın üstünde bulunur.)yaparak  (python dcbot.py) yazıp 
ENTER'a basarsanız hatalarınızı ve botun kontrolünü gerçekleştirebilirsiniz.


# Setting `Playing ` status
await bot.change_presence(activity=discord.Game(name="a game"))

# Setting `Streaming ` status
await bot.change_presence(activity=discord.Streaming(name="My Stream", url=my_twitch_url))

# Setting `Listening ` status
await bot.change_presence(activity=discord.Activity(type=discord.ActivityType.listening, name="a song"))

# Setting `Watching ` status
await bot.change_presence(activity=discord.Activity(type=discord.ActivityType.watching, name="a movie"))
