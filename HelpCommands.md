Thank you for choosing CyberBlue as your discord bot!

Here is the help command that you (or someone else...) worked your little fingertips on that greasy keyboard of yours for!
Command key (,) ex. ,help  

  Commands
Moderation Commands

       ,ban -- bans a user (permission locked command)
       ,kick -- kicks a user (permission locked command) ]
```py
        async def ban(ctx, member: discord.Member, *, reason=None):
	           await member.ban(reason=reason)
	            await ctx.send(f'User {member} has been **obliterated** from this universe
```
		   

######

Misc Commands

       ,ping --<Bot's ping>
       ,debug --</debug bot>
       ,test --<test if bot is working>
       ,aboutus --<about us

######

Server Commands

	,servers [Checks current servers the bot is in]
       ,purge {NO LIMIT PURGES}
       ,annoy (ADMIN LOCKED) - DONT USE FOR BAD INTENTS!
```py

	@bot.command()
	@has_permissions(administrator=True)
		 async def annoy(ctx):
    			 await ctx.send("@everyone")
	------------------------------------------------------------------
	@annoy.error
	async def annoy(ctx, error):
 	   if isinstance(error, commands.MissingPermissions):
    		await ctx.send("you cant annoy a server that you dont moderate!11!!111")



```



######

Reaction Roles

       ,reactionroles (ADMIN LOCKED)

######

Jokes/Memes
	
	,jeston
	,lean
	,leanrecipe
	,jokes (RANDOM JOKE, HUGE LIBRARY)





######

## [Discord Server](https://discord.gg/az7n3TAk5r)
<a href="https://discord.gg/az7n3TAk5r"><img src="https://cdn.discordapp.com/attachments/921216391074443314/956930217052631060/image_39.png"></a>
