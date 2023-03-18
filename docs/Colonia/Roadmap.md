Future Plans
========

## Better Main Menu
It's not the best

## Website
- finish ‘News & Announcements’ part
- Add link for donation shop and curseforge

## Colonia v1.14  
**New Mods:**

- [Illuminations (Client-Side)](https://www.curseforge.com/minecraft/mc-mods/illuminations-forge)  
- Hexerei  
- [Ping](https://www.curseforge.com/minecraft/mc-mods/ping)  
- [Void Totem](https://www.curseforge.com/minecraft/mc-mods/voidtotem)  
- [Charm of Undying](https://www.curseforge.com/minecraft/mc-mods/charm-of-undying)  
- [BetterEnd](https://www.curseforge.com/minecraft/mc-mods/betterend-forge-port)  
- [Deadly End Phantoms](https://www.curseforge.com/minecraft/mc-mods/deadly-end-phantoms)  
- [Waystones2Waypoints](https://www.curseforge.com/minecraft/mc-mods/waystones2waypoints)  
- [Just Enough Professions (JEP)](https://www.curseforge.com/minecraft/mc-mods/just-enough-professions-jep)  
- [More Villagers](https://www.curseforge.com/minecraft/mc-mods/more-villagers)  

| Name                 | Type | Notes                              | Core Mod                       |
|----------------------|------|------------------------------------|--------------------------------|
| Star Worm Equestrian |      | May conflict with third person mod | Player Animation Lib</br> Geckolib |
| The Abyss II         |      |                                    |                                |

*Update (to test in dev)*

- MCA Reborn
- Architectury

*Remove*

- RecipeBuffers?

## To Do List

- Fix blur mod blurring entire MCA interface
- Setup donation store
- Configure Client Tweaks
- Add Inventory Tweaks Renewed to server

## Current Bugs

### Server may randomly freeze and not start back up.

Status: <span style="color:red">Investigating</span>

Please message a staff member if the server doesn't start up again within 10 minutes.

### Random client crash when rendering snow chunks

Status: <span style="color:red">Investigating</span>

Please create a ticket and send the latest crash report txt file and your latest.log, not your crashy link.
```
Description: Unexpected error

java.util.ConcurrentModificationException: null
	at java.util.ArrayList$ArrayListSpliterator.tryAdvance(ArrayList.java:1353) ~[?:1.8.0_51] {}
	at java.util.stream.ReferencePipeline.forEachWithCancel(ReferencePipeline.java:126) ~[?:1.8.0_51] {}
	at java.util.stream.AbstractPipeline.copyIntoWithCancel(AbstractPipeline.java:529) ~[?:1.8.0_51] {}
	at java.util.stream.AbstractPipeline.copyInto(AbstractPipeline.java:516) ~[?:1.8.0_51] {}
	at java.util.stream.AbstractPipeline.wrapAndCopyInto(AbstractPipeline.java:502) ~[?:1.8.0_51] {}
	at java.util.stream.FindOps$FindOp.evaluateSequential(FindOps.java:152) ~[?:1.8.0_51] {}
	at java.util.stream.AbstractPipeline.evaluate(AbstractPipeline.java:234) ~[?:1.8.0_51] {}
	at java.util.stream.ReferencePipeline.findAny(ReferencePipeline.java:469) ~[?:1.8.0_51] {}
	at org.orecruncher.environs.handlers.CommonStateHandler.process(CommonStateHandler.java:114) ~[?:4.0.5.0] {re:classloading,pl:eventbus:A,pl:runtimedistcleaner:A}
	at org.orecruncher.environs.handlers.Manager.onTick(Manager.java:124) ~[?:4.0.5.0] {re:classloading}
	at org.orecruncher.environs.handlers.Manager.clientTick(Manager.java:141) ~[?:4.0.5.0] {re:classloading}
```
Environs is part of the sound system in Dynamic Surroundings. 

### Sleep Vote

Status: <span style="color:red">Investigating</span>

Seems to only work if theres more than 4 people online. 

### Certus Quartz Seed don't grow inside of crystal growth accelerators

Status: <span style="color:red">Workaround Required</span>

Use the Enrichment Chamber from Mekanism instead.

### Client crash with Rubidium v0.2.10

Status: <span style="color:green">Fix Found</span>

Issue with mixin conflict, stick with version 0.2.9