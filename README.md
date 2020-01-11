# Installation Instructions
> - Add the "servercommands" folder to your Server Resources

> - Append "start servercommands" in your server.cfg

**Save and Profit, Nice and simple 😁** 

# Enable FiveMToDiscord Logs Support
> - Find this line 
``
--[[ TriggerEvent('DiscordBot:ToDiscord', 'chat', GetPlayerName(id) .. ' [ID: ' .. GetPlayerServerId(id) .. ']', data.message, 'steam', GetPlayerServerId(id), false, true) ]]
``

> - And remove the
``
-- [[ ]]
``

THIS NEEDS TO BE DONE FOR MULTIPLE LINES.
