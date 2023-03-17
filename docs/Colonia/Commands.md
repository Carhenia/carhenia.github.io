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


/help

Shows a list of server or plugin commands 

### GriefDefender

/gd help 

Shows a list of server or plugin commands 

### Claims

/gd abandon claim

Arguments: ```[identifier]``` Abandons a claim

/gd abandon all

Abandons ALL your claims

/gd abandon top

Abandons a claim and all its subdivisions

/gd buy claim

View a list of claims for sale. Click ```[Buy]``` to purchase.

/gd claim contract

Aliases: claimcontract, contractclaim

Arguments: ```<amount> [direction] [identifier]```

Contracts/Shrinks the claim from the direction you are facing.

/gd claim create

Aliases: claimcreate

Arguments: ```<radius> [type]```

Creates a claim around the player of the given type. If no claimtype (or an incorrect one) is specified, a basic claim will be created.

/gd claim expand

Aliases: claimexpand, expandclaim

Arguments: ```<amount> [direction] [identifier]```

Expands the claim in the direction you are facing.

/gd claim farewell

Arguments: ```<message> [identifier]```

Sets the farewell message of your claim

To unset, /gd claim farewell clear

/gd claim greeting

Arguments: ```<message> [identifier]```

Sets the greeting message of your claim

To unset, /gd claim greeting clear

/gd claim id

Arguments: ```<identifier>```

Sets the friendly identifier of your claim.

/gd claim info

Aliases: claiminfo

Arguments: ```[identifier]```

Gets information about a claim you are standing in or by claim id.

/gd claim inherit

Aliases: inherit

Toggles parent claim inherit mode

/gd claim inspect

Aliases: claiminspect

Arguments: ```[area|hide|hideall]```

Inspects the target block player is looking at or nearby claims.

/gd claim list

Aliases: claimlist

Arguments: ```[<player> [world]]```

List information about a player's claims.

/gd claim displayname

Arguments: ```<name>```

Sets the display name of your claim

/gd claim rent

Arguments: ```create [<rate> [<max_days>]]|info|list|cancel]```

Used to rent/list claims.

Note: Requires economy plugin.

/gd claim setspawn

Aliases: claimsetspawn

Sets the spawn of your claim to the location you are standing in.

/gd claim spawn

Aliases: claimspawn

Teleports you to claim spawn, if available.

/gd claim tax

Arguments: ```balance|force|pay <amount>]```

Used to manage taxes of a claim.

Note: The argument force allows an admin to pay a claim's tax balance for another player.

Note: Requires economy plugin.

/gd claim transfer

Aliases: transferclaim

Arguments: ```<player> [identifier]```

Transfer the claim you're standing in to a player.

/gd claimgroup player

Arguments: ```join <group> [<identifier>]|unjoin [<identifier>]|create <group>|delete <group>```

Used to manage player claim groups.

/gd cuboid

Aliases: cuboid

Toggles 3D cuboid claims mode.

/gd mode basic

Aliases: modebasic

Switches the shovel tool back to basic claims mode.

/gd mode subdivide

Aliases: modesubdivide

Switches the shovel tool to subdivision mode, used to subdivide your claims

/gd mode town

Aliases: modetown

Switches the shovel tool back to town claims mode.

/gd player transferblocks

Aliases: transferblocks

Arguments: ```<player> <amount>```

Gives claim blocks to another player

/gd player trapped

Aliases: trapped

Teleports the player to a safe location if stuck and unable to build.

/gd player unlockdrops

Aliases: unlockdrops

Allows other players to pickup any items dropped from death.

/gd sell claim

Arguments: ```<price>```

Puts your claim up for sale at the set price. To disable sale, set the price to -1 or set ForSale setting in /claiminfo to false.

Flag

/gd flag debug

Aliases: cfd

Toggles claim flag debug mode

/gd flag claim

Aliases: cf

Arguments: ```[<flag> <target> <value> [<contexts>]]```

Gets/Sets claim flags in the claim you are standing in.

/gd flag definition

Aliases: cf

Arguments: ```<preset:group> <definition> <value> [identifier]```

Sets claim flag definitions in the claim you are standing in or claim identifier.

/gd flag group

Aliases: cfg

Arguments: ```<group> <flag> <target> <value> [<contexts>]]```

Gets/Sets flag permission for a group in claim you are standing in.

/gd flag player

Aliases: cfp

Arguments: ```<player> <flag> <target> <value> [<contexts>]]```

Adds flag permission to player.

/gd flag reset

Aliases: cfr

Resets a claim to flag defaults.

Options

/gd option claim

Aliases: co

Arguments: ```[<option> <value> [<contexts>]]```

Gets/Sets options in the claim you are standing in.

/gd option group

Aliases: cog

Arguments: ```<group> [<option> <value> [<contexts>]]```

Gets/Sets options for a group in claim you are standing in.

/gd option player

Aliases: cop

Arguments: ```<player> [<option> <value> [<contexts>]]```

Gets/Sets options for a player in claim you are standing in.

Trust

/gd trust player

Accessor: Grants a player entry to your claim(s) and use of your bed

Container: Grants a player access to your claim's containers, crops, animals, bed, buttons, and levers

Builder: Grants a player edit access to your claim(s)

Manager: Grants a player access to all of the above including claim settings

Aliases: trust

Arguments: ```<player>|public <trusttype>```

Grants a player access to your claim(s).

/gd trust group

Accessor: Grants a group entry to your claim(s) and use of your bed

Container: Grants a group access to your claim's containers, crops, animals, bed, buttons, and levers

Builder: Grants a group edit access to your claim(s)

Manager: Grants a group access to all of the above including claim settings

Aliases: trustgroup

Arguments: ```<group>|public <trusttype>```

Grants a group access to your claim(s)

/gd trustall player

Accessor: Grants a player entry to ALL your claim(s) and use of your bed

Container: Grants a player access to ALL your claim's containers, crops, animals, bed, buttons, and levers

Builder: Grants a player edit access to ALL your claim(s)

Manager: Grants a player access to all of the above including claim settings Aliases: trust

Arguments: ```<player>|public <trusttype>```

Grants a player access to ALL your claim(s).

/gd trustall group

Accessor: Grants a group entry to ALL your claim(s) and use of your bed

Container: Grants a group access to ALL your claim's containers, crops, animals, bed, buttons, and levers

Builder: Grants a group edit access to ALL your claim(s)

Manager: Grants a group access to all of the above including claim settings Aliases: trustallgroup

Arguments: ```<group>|public <trusttype>```

Grants a group access to ALL your claim(s).

/gd untrust player

Aliases: untrust

Arguments: ```<player>|public```

Revokes a player's access to your claim.

/gd untrust group

Aliases: untrustgroup

Arguments: ```group>|public```

Revokes a group's access to your claim.

/gd untrustall player

Aliases: untrustall

Arguments: ```<player>|public```

Revokes a player's access to ALL your claim(s).

/untrustall group

Aliases: untrustallgroup

Arguments: ```<group>|public```

Revokes a group's access to ALL your claim(s).

/gd trust list

Lists permissions for the claim you're standing in

### Essentials

/spawn

Teleport to the spawnpoint.

/playtime

Shows your total playtime

/warpinfo ```<warp>```

 Finds location information for a specified warp.

/warp

 List all warps or warp to the specified location.

/tpa

Request to teleport to the specified player.

/exp

View your xp level

/tpdeny

Rejects teleport requests.

/tpacancel

Cancel all outstanding teleport requests. Specify ```[player]``` to cancel requests with them.

/tpaccept

Accepts teleport requests.

/tpahere

Request that the specified player teleport to you.

/delhome

Deletes a home

/sethome

Set home to your current location.

/home

Teleport to your home.

/rules

Views the server rules.

/realname

Displays the username of a user based on nick.

/rtoggle

Change whether the recipient of the reply is last recipient or last sender.

/r

Quickly reply to the last player to message you.

/ping

/paytoggle

Toggles whether you are accepting payments.

/payconfirmtoggle

Toggles whether you are prompted to confirm payments.

/pay

Pays another player from your balance.

/near

Lists the players near by or around a player.

/msgtoggle

Blocks receiving all private messages.

/msg

Sends a private message to the specified player.

/motd

Views the Message Of The Day.

/mail

Manages inter-player, intra-server mail.

/list

List all online players.

/info

Shows information set by the server owner.

/ignore

Ignore or unignore other players.

/helpop

Message online staff members.

/getpos

Get your current coordinates or those of a player.

/depth

States current depth

/balance

Pays another player from your balance.

/balancetop

Lists players by top balances.

/afk

Marks you as away-from-keyboard.

DiscordSRV

/discord help, /discord ?

Shows a list of all the options you have permissions for

/discord link

Sends you instructions to link your Minecraft account with your Discord account.

/discord linked

Shows if your Minecraft account is linked with a discord account.

/discord unlink, /discord clearlinked

Unlink your Discord account from your Minecraft account.

QuickShop

/qs find ```<item>```

Find a specific item in a nearby shop.

/qs staff

BetterSleeping

/bs buffs

See the list of (de)buffs you can get

/bs shout

Anonymously ask players in your world to sleep

/bs status

View the current status of your world.

Misc

/report ```<target> reason>```

Report a target to the staff team for investigation. 

/tl toggle

Toggle on/off the animated tablist

/warnings

View own warnings

/pwarp

GUI Management for player warps

/kit

Displays all available kits. 