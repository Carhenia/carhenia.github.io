Commands
========

Plugins
-------

The following plugins are used on our Colonia Server. Their base commands are included in this page, however, more information about them will be available on their spigot page. 

[Player Warps](https://www.spigotmc.org/resources/%E2%AD%90-player-warps-%E2%AD%90-%E2%9E%A2-let-your-players-set-warps-1-7-1-19.66692/)  
[QuickShop](https://www.spigotmc.org/resources/quickshop-reremake-1-19-ready-multi-currency.62575/)  
[GriefDefender](https://www.spigotmc.org/resources/1-12-2-1-19-griefdefender-claim-plugin-grief-prevention-protection.68900/)  

Permissions
-----------

This page outlines the commands default players have access to

### Minecraft


<span style="color:green">/help</span>

Shows a list of server or plugin commands 

### GriefDefender

<span style="color:green"><span style="color:green">/gd help</span>

Shows a list of server or plugin commands 

### Claims

<span style="color:green">/gd abandon claim</span>

Arguments: ```[identifier]``` Abandons a claim

<span style="color:green">/gd abandon all</span>

Abandons ALL your claims

<span style="color:green">/gd abandon top</span>

Abandons a claim and all its subdivisions

<span style="color:green">/gd buy claim</span>

View a list of claims for sale. Click ```[Buy]``` to purchase.

<span style="color:green">/gd claim contract</span>

Aliases: claimcontract, contractclaim

Arguments: ```<amount> [direction] [identifier]```

Contracts/Shrinks the claim from the direction you are facing.

<span style="color:green">/gd claim create</span>

Aliases: claimcreate

Arguments: ```<radius> [type]```

Creates a claim around the player of the given type. If no claimtype (or an incorrect one) is specified, a basic claim will be created.

<span style="color:green">/gd claim expand</span>

Aliases: claimexpand, expandclaim

Arguments: ```<amount> [direction] [identifier]```

Expands the claim in the direction you are facing.

<span style="color:green">/gd claim farewell</span>

Arguments: ```<message> [identifier]```

Sets the farewell message of your claim

To unset, <span style="color:green">/gd claim farewell clear</span>

<span style="color:green">/gd claim greeting</span>

Arguments: ```<message> [identifier]```

Sets the greeting message of your claim

To unset, <span style="color:green">/gd claim greeting clear</span>

<span style="color:green">/gd claim id</span>

Arguments: ```<identifier>```

Sets the friendly identifier of your claim.

<span style="color:green">/gd claim info</span>

Aliases: claiminfo

Arguments: ```[identifier]```

Gets information about a claim you are standing in or by claim id.

<span style="color:green">/gd claim inherit</span>

Aliases: inherit

Toggles parent claim inherit mode

<span style="color:green">/gd claim inspect</span>

Aliases: claiminspect

Arguments: ```[area|hide|hideall]```

Inspects the target block player is looking at or nearby claims.

<span style="color:green">/gd claim list</span>

Aliases: claimlist

Arguments: ```[<player> [world]]```

List information about a player's claims.

<span style="color:green">/gd claim displayname</span>

Arguments: ```<name>```

Sets the display name of your claim

<span style="color:green">/gd claim rent</span>

Arguments: ```create [<rate> [<max_days>]]|info|list|cancel]```

Used to rent/list claims.

Note: Requires economy plugin.

<span style="color:green">/gd claim setspawn</span>

Aliases: claimsetspawn

Sets the spawn of your claim to the location you are standing in.

<span style="color:green">/gd claim spawn</span>

Aliases: claimspawn

Teleports you to claim spawn, if available.

<span style="color:green">/gd claim tax</span>

Arguments: ```balance|force|pay <amount>]```

Used to manage taxes of a claim.

Note: The argument force allows an admin to pay a claim's tax balance for another player.

Note: Requires economy plugin.

<span style="color:green">/gd claim transfer</span>

Aliases: transferclaim

Arguments: ```<player> [identifier]```

Transfer the claim you're standing in to a player.

<span style="color:green">/gd claimgroup player</span>

Arguments: ```join <group> [<identifier>]|unjoin [<identifier>]|create <group>|delete <group>```

Used to manage player claim groups.

<span style="color:green">/gd cuboid</span>

Aliases: cuboid

Toggles 3D cuboid claims mode.

<span style="color:green">/gd mode basic</span>

Aliases: modebasic

Switches the shovel tool back to basic claims mode.

<span style="color:green">/gd mode subdivide</span>

Aliases: modesubdivide

Switches the shovel tool to subdivision mode, used to subdivide your claims

<span style="color:green">/gd mode town</span>

Aliases: modetown

Switches the shovel tool back to town claims mode.

<span style="color:green">/gd player transferblocks</span>

Aliases: transferblocks

Arguments: ```<player> <amount>```

Gives claim blocks to another player

<span style="color:green">/gd player trapped</span>

Aliases: trapped

Teleports the player to a safe location if stuck and unable to build.

<span style="color:green">/gd player unlockdrops</span>

Aliases: unlockdrops

Allows other players to pickup any items dropped from death.

<span style="color:green">/gd sell claim</span>

Arguments: ```<price>```

Puts your claim up for sale at the set price. To disable sale, set the price to -1 or set ForSale setting in /claiminfo to false.

Flag

<span style="color:green">/gd flag debug</span>

Aliases: cfd

Toggles claim flag debug mode

<span style="color:green">/gd flag claim</span>

Aliases: cf

Arguments: ```[<flag> <target> <value> [<contexts>]]```

Gets/Sets claim flags in the claim you are standing in.

<span style="color:green">/gd flag definition</span>

Aliases: cf

Arguments: ```<preset:group> <definition> <value> [identifier]```

Sets claim flag definitions in the claim you are standing in or claim identifier.

<span style="color:green">/gd flag group</span>

Aliases: cfg

Arguments: ```<group> <flag> <target> <value> [<contexts>]]```

Gets/Sets flag permission for a group in claim you are standing in.

<span style="color:green">/gd flag player</span>

Aliases: cfp

Arguments: ```<player> <flag> <target> <value> [<contexts>]]```

Adds flag permission to player.

<span style="color:green">/gd flag reset</span>

Aliases: cfr

Resets a claim to flag defaults.

Options

<span style="color:green">/gd option claim</span>

Aliases: co

Arguments: ```[<option> <value> [<contexts>]]```

Gets/Sets options in the claim you are standing in.

<span style="color:green">/gd option group</span>

Aliases: cog

Arguments: ```<group> [<option> <value> [<contexts>]]```

Gets/Sets options for a group in claim you are standing in.

<span style="color:green">/gd option player</span>

Aliases: cop

Arguments: ```<player> [<option> <value> [<contexts>]]```

Gets/Sets options for a player in claim you are standing in.

Trust

<span style="color:green">/gd trust player</span>

Accessor: Grants a player entry to your claim(s) and use of your bed

Container: Grants a player access to your claim's containers, crops, animals, bed, buttons, and levers

Builder: Grants a player edit access to your claim(s)

Manager: Grants a player access to all of the above including claim settings

Aliases: trust

Arguments: ```<player>|public <trusttype>```

Grants a player access to your claim(s).

<span style="color:green">/gd trust group</span>

Accessor: Grants a group entry to your claim(s) and use of your bed

Container: Grants a group access to your claim's containers, crops, animals, bed, buttons, and levers

Builder: Grants a group edit access to your claim(s)

Manager: Grants a group access to all of the above including claim settings

Aliases: trustgroup

Arguments: ```<group>|public <trusttype>```

Grants a group access to your claim(s)

<span style="color:green">/gd trustall player</span>

Accessor: Grants a player entry to ALL your claim(s) and use of your bed

Container: Grants a player access to ALL your claim's containers, crops, animals, bed, buttons, and levers

Builder: Grants a player edit access to ALL your claim(s)

Manager: Grants a player access to all of the above including claim settings Aliases: trust

Arguments: ```<player>|public <trusttype>```

Grants a player access to ALL your claim(s).

<span style="color:green">/gd trustall group</span>

Accessor: Grants a group entry to ALL your claim(s) and use of your bed

Container: Grants a group access to ALL your claim's containers, crops, animals, bed, buttons, and levers

Builder: Grants a group edit access to ALL your claim(s)

Manager: Grants a group access to all of the above including claim settings Aliases: trustallgroup

Arguments: ```<group>|public <trusttype>```

Grants a group access to ALL your claim(s).

<span style="color:green">/gd untrust player</span>

Aliases: untrust

Arguments: ```<player>|public```

Revokes a player's access to your claim.

<span style="color:green">/gd untrust group</span>

Aliases: untrustgroup

Arguments: ```group>|public```

Revokes a group's access to your claim.

<span style="color:green">/gd untrustall player</span>

Aliases: untrustall

Arguments: ```<player>|public```

Revokes a player's access to ALL your claim(s).

/untrustall group

Aliases: untrustallgroup

Arguments: ```<group>|public```

Revokes a group's access to ALL your claim(s).

<span style="color:green">/gd trust list</span>

Lists permissions for the claim you're standing in

### Essentials

<span style="color:green">/spawn</span>

Teleport to the spawnpoint.

<span style="color:green">/playtime</span>

Shows your total playtime

<span style="color:green">/warpinfo ```<warp>```</span>

 Finds location information for a specified warp.

<span style="color:green">/warp</span>

 List all warps or warp to the specified location.

<span style="color:green">/tpa</span>

Request to teleport to the specified player.

<span style="color:green">/exp</span>

View your xp level

<span style="color:green">/tpdeny</span>

Rejects teleport requests.

<span style="color:green">/tpacancel</span>

Cancel all outstanding teleport requests. Specify ```[player]``` to cancel requests with them.

<span style="color:green">/tpaccept</span>

Accepts teleport requests.

<span style="color:green">/tpahere</span>

Request that the specified player teleport to you.

<span style="color:green">/delhome</span>

Deletes a home

<span style="color:green">/sethome</span>

Set home to your current location.

<span style="color:green">/home</span>

Teleport to your home.

<span style="color:green">/rules</span>

Views the server rules.

<span style="color:green">/realname</span>

Displays the username of a user based on nick.

<span style="color:green">/rtoggle</span>

Change whether the recipient of the reply is last recipient or last sender.

<span style="color:green">/r</span>

Quickly reply to the last player to message you.

<span style="color:green">/ping</span>

<span style="color:green">/paytoggle</span>

Toggles whether you are accepting payments.

<span style="color:green">/payconfirmtoggle</span>

Toggles whether you are prompted to confirm payments.

<span style="color:green">/pay</span>

Pays another player from your balance.

<span style="color:green">/near</span>

Lists the players near by or around a player.

<span style="color:green">/msgtoggle</span>

Blocks receiving all private messages.

<span style="color:green">/msg</span>

Sends a private message to the specified player.

<span style="color:green">/motd</span>

Views the Message Of The Day.

<span style="color:green">/mail</span>

Manages inter-player, intra-server mail.

<span style="color:green">/list</span>

List all online players.

<span style="color:green">/info</span>

Shows information set by the server owner.

<span style="color:green">/ignore</span>

Ignore or unignore other players.

<span style="color:green">/helpop</span>

Message online staff members.

<span style="color:green">/getpos</span>

Get your current coordinates or those of a player.

<span style="color:green">/depth</span>

States current depth

<span style="color:green">/balance</span>

Pays another player from your balance.

<span style="color:green">/balancetop</span>

Lists players by top balances.

<span style="color:green">/afk</span>

Marks you as away-from-keyboard.

DiscordSRV

<span style="color:green">/discord help, /discord ?</span>

Shows a list of all the options you have permissions for

<span style="color:green">/discord link</span>

Sends you instructions to link your Minecraft account with your Discord account.

<span style="color:green">/discord linked</span>

Shows if your Minecraft account is linked with a discord account.

<span style="color:green">/discord unlink, /discord clearlinked</span>

Unlink your Discord account from your Minecraft account.

QuickShop

<span style="color:green">/qs find ```<item>```</span>

Find a specific item in a nearby shop.

<span style="color:green">/qs staff</span>

BetterSleeping

<span style="color:green">/bs buffs</span>

See the list of (de)buffs you can get

<span style="color:green">/bs shout</span>

Anonymously ask players in your world to sleep

<span style="color:green">/bs status</span>

View the current status of your world.

Misc

<span style="color:green">/report ```<target> reason>```</span>

Report a target to the staff team for investigation. 

<span style="color:green">/tl toggle</span>

Toggle on/off the animated tablist

<span style="color:green">/warnings</span>

View own warnings

<span style="color:green">/pwarp</span>

GUI Management for player warps

<span style="color:green">/kit</span>

Displays all available kits. 