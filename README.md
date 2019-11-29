# Galactic Couriers  
**NOTE:** if updating from an older version, make sure that files "mission.txt" and "jobs.txt" are *not* present in the plugin's data folder.
___  
### Description  
Galactic Couriers is a plugin for the game [Endless Sky](https://github.com/endless-sky/endless-sky). It tells a story of a small breakaway community of humans, who (with the help of the player) manage to discover an uninhabited cluster of star systems, settle it, and become a fully-fledged faction.
___
### Installation  
The installation process is the same as all other ES plugins. Once you download the plugin, place the *galactic-couriers* folder into your game's *plugins* folder. This folder by default is in *C:\Users\YourUserName\AppData\Roaming\endless-sky* on Windows.  
This plugin *should* work just fine even when applied to an already well-progressed game, but it is still advised to backup your save game when installing *any* plugin.  
I am not responsible for your save breaking, but if it does I'll be happy to help you fix it, just open a new issue.  
___  
### How to start  
Once the plugin is installed, you will notice a single new star system appearing on your map. You won't be able to interact with it in any way until you finish the first mission, though.  
This mission becomes available once you finish the main story and make contact with all alien races. The mission starts randomly when entering a spaceport on any human planet. Here are the full conditions:  
<details>

	source
		government "Free Worlds" "Republic" "Syndicate"
	to offer
		has "First Contact: Hai: offered"
		has "First Contact: Remnant: offered"
		has "First Contact: Wanderer: offered"
		has "Coalition: First Contact: offered"
		has "main plot completed"
		random >= 75

</details>  

___  
### TO-DO List  
***Spoilers ahead***
- [ ] Add options to defer or skip all non-critical missions
- [ ] Create jobs unique to the Courier star cluster
- [ ] **Conclude chapter 2** *(after all the other things are done)*
- [ ] Create custom outfits for the Ar'leng
- [ ] Add a side-story with levelled boss fights
- [ ] Add an option to adopt the Courier ship swizzle
- [ ] Create custom hails for Courier pilots
- [ ] Create custom news popups for Courier spaceports

___
### Story overview  
***Even more spoilers ahead! Do not read this if you're actually interested in downloading the plugin and playing through the story. The only reason I'm writing this is so that if you have a suggestion for the story you have a place to read up on the full context of the plugin's lore.***  
I want the story of this plugin to be divided into separate "chapters", with each chapter having an interesting introduction and conclusion.  

The Couriers intitially started as a company under the Republic called the Galactic Couriers *(hence the weird name of the plugin)*, but as they became more and more successful their leaders and even employees started to receive threats from anonymous sources *(I wanted to imply that it was the Syndicate and the Parliament because the Couriers began to have too much power for their liking, but given that the storylines for the Republic and the Syndicate don't exist yet I just kept it anonymous)*.  
The Couriers pretended to disband their company, but instead they secretely moved their operations into a lonely star system far from the Republic's reach. This star system, called "Meliter" is unique because it is the only known stable triple star system, and also contains an abandoned Kor Sestor station that the Couriers modified to serve as their home.  
From there, they continued to serve as a transport company, but instead of general cargo transport they now helped with things like humanitarian aid, relocation of refugees of war, or simply delivering goods to private customers who feel like their stuff is safer with the Couriers rather than some inexperienced pilot. The Couriers primarily use Bulk Freighters equipped with Jump Drives *(they get the drives from Korath raids, they managed to move some warship to their system to defend against them)* but disguised as merchant ships.  

#### Chapter 1  

Your first contact with the Couriers (besides randomly stumbling upon their star system) is one of their Bulk Freighters landing in the same spaceport as you. It turns out that this particular freighter often appears on this planet with deliveries of exotic goods for some local rich retiree. You have the option to approach the ship, where you meet one of the retiree's private guards who oversees the unloading, but he recognizes you and tells you perhaps more than he's allowed to. From this information you learn that there are rumors that this ship comes from a star system "up north".  
If you refuse to inspect the ship, you are then given a second option to unlock the Courier mission arc in the form of a disabled Courier ship in a random uninhabited star system. Once you assist it, its crew will thank you and tell you to meet their boss in the Courier star system.  

Once you first land on the Courier space station, you meet up with their CEO Vladimir Novak. He recognizes that you have a Jump Drive and a lot of experience with the Korath and other aliens alike, and offers you to do some work for them. This work is mainly composed of simple cargo transport missions. After you do a few of the Courier jobs, the station gets attacked by a Korath raid.  
This raid is much bigger than anything they experienced before and consumes a big chunk of the Courier fleet (although they do manage to capture few Korath Raiders and Chasers). Because of this, the Couriers come up with a plan to prepare for future raids; they ask the Remnant to give them access to their shipyards. The Remnant agree, but only partially, allowing the Couriers to purchase only the Starling warship *(the reason I thought the Remnant would help is because both the Couriers and Remnant are in a similar situation; a breakaway group of humans living in separation, constatly threatened by the Korath - although further in the story the similarities start to fade away)*.  
The Couriers decide to use the Starling to its full potential, and exploit its cloaking ability to set up early warning systems around nearby star, so at the very least they have time to evacuate civilians from their station. Thanks to this they soon notice the Korath preparing for another - even larger - raid. Because the Couriers have very little warships, and buying new ships in the human space would raise too much suspicion, they get in contact with one of their long-time customers who lives in the Hai space and they acquire a fleet of Shield Beetles.  
Once again you help them defeat the Korath raid, but shortly before that you are also intorduced to Christian Zimmerman (Chris), a chief Courier scientist who is in charge of translating old Kor Sestor information database that was left on the station.

After the raid, Chris finds out that this star system was abandoned by the Kor Sestor because an alien entity appeared here and slaughtered most of them. Later it is also revealed that the space station is in fact one large weapon designed by the Sestor to create temporary hyperspace links and use them to channel energy of three stars at once to its target system. This weapon misfired at some point, and due to some weird anomaly managed to link with an alien star system at the edge of the observable universe, which is how this alien entity (a warship) got there.  
You and Chris then attempt to trace the steps of the alien ship, because Chris thinks that the ship left the system and went somewhere else into hiding. However, after you come up empty-handed, Chris realizes that this alien ship is still in the Courier system. When it defeated the Sestor, it travelled to the far edge of the solar system and went into a deep state of hibernation, only to be woken up by the recent fights with the Korath. Now this ship is headed towards the Courier station, so evacuation starts.  
After analyzing the ship, Chris realizes that the only way it can be destroyed is by forcing all three stars in the system to go supernova. To do this, Chris wants to use the station's weapon to knock one of the three stars out of its orbit so it would collapse into the other two.  
Meanwhile, the Korath are preparing for another huge raid, which arrives almost at the same time as the alien ship. You escort the last batch of Courier transport ships out of the system, while Chris stays behind in the station to operate the weapon. He also set up special solar-powered shields in the hope that he and the station will be able to withstand the full force of three stars exploding.  
Once you and the Courier transports arrive at your destination, the star system is temporarily deleted from your map and you all go your separate ways.  

#### Chapter 2
