# Multiplayer Percentage Sleeping System

## What it does

This Datapack is intended for larger survival servers. It allows the OPs of the server to set a percentage of players required to sleep to skip the night.
So if you want to skip the night if half of the players playing are in a bed, set the percentage to 50%.

When a player is trying to pass the night, a message in chat with how many players are left as well as an advancement will make other online players aware of this intent.

## How to set up

Download the zip file and place it into your `world/datapacks` folder. If the world is already running, run `reload`. That's all you need to do.  
That way it has been set to **10% as a standard**. To change that, use the following command in chat (replace XX with your desired percentage):

    scoreboard players set requiredPercent multSleep.count XX

This number can be changed at any time you want.
	
## Further Information

This datapack will...

* ...always require a minimum of 1 player to sleep.  
* ...round down the required players. So if the percentage is set to 50% and 3 players are online, 1.5 players need to sleep, which the pack rounds down to one.  
* ...clear the weather whenever the night is skipped.  
* ...not interfere with the phantom timer. If you are in a bed, the timer resets, as always.  
* ...only consider players in the overworld when counting how many players need to sleep.
* ...add to the time instead of setting it, so you won't loose your time played/ingame days

### Contact

If you have any questions, concerns, praise or found a bug, you can contact me directly at [contact@plagiatus.net](mailto:contact@plagiatus.net) or use my [contact form](http://plagiatus.net/#contact).