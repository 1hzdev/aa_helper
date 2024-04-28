# AA Helper

[Invite the bot](https://discord.com/api/oauth2/authorize?client_id=1012987338160341133&permissions=0&scope=bot+applications.commands)

AA Helper is a discord bot made for Anime Adventures players. This bot is not affiliated with the developers of the game.

This repo contains files for the bot to work + a feature list and other information about the bot can be found below.

Source code for the bot will probably not be released publicly.
## Commands & Features
- /stats - Shows damage, range, and SPA for a unit in game at max upgrade. Takes one string parameter which should be the name of the unit. A second parameter is accepted, read below

- /reroll - Simulates trait rerolling from Anime Adventures. Takes one integer parameter up to 1000

- /trait - Simulates rerolling for a specific trait. Takes one string parameter which should be the name of a mythic trait

- /traitinfo - Shows information about a trait. Takes one string parameter which should be the name of a trait

- /verify - Add yourself to the whitelist, allowing you to roll more traits at once. Must be used in the bot's discord server found above

- /event - See any running bot events

- /game - Shows information about a game. Takes one integer parameter which should be a placeid

- /player - Shows information about a user. Takes one integer parameter which should be a username

- /help - Help command lol

- Custom emojis for various commands

## Stat Lookup Guide
Running the command below will show the stats for "Guts" at max upgrade, without traits, and with base stats (0% Damage / 0% Range / 0% SPA)

![image](https://github.com/1hzdev/aa_helper/assets/81895838/5dd11627-3b41-45ee-bb73-c4fc9416f44e)

Now, to view his SSS stats, you can fill out the "mode" field with "sss" to see his SSS stats (20% Damage / 20% Range / 20% SPA)

![image](https://github.com/1hzdev/aa_helper/assets/81895838/57a09f97-1351-4dda-a1d0-c2d219c11640)

You can also use any trait in the game, and see the unit's stats with that trait

![image](https://github.com/1hzdev/aa_helper/assets/81895838/aabfd781-622b-4da2-9776-de6f25420c7f) 

Keep in mind that for tiered traits, such as Superior 1, Nimble 2, etc. there is no difference and you can just type it as normal. Also, adept and culling are not implemented for obvious reasons

This command is in beta and will improve with time, if you encounter an error, please report it by dming me

## Credit

 - [Data for !stats](https://docs.google.com/spreadsheets/d/1bHwjTTrJcxNn6WhuTZQ7i_iLfsbx7GAQy4NTWztpKw8/edit#gid=1453364345)
 - [Data for !traitinfo](https://animeadventures.fandom.com/wiki/Traits)

## Feedback

If you have any feedback, please reach out to me at @1hz on discord


## Authors

- [@1hz](https://www.github.com/1hzdev)
