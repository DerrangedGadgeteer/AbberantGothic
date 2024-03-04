# Intro level: Investigating the Theater Cult

## Opening Crawl:

The Villiage of Lyndale has been troubled by the emergence of a strange cult, rallying around a demagogue figure they call "The Grand Deacon."  Initially the cult was a mere nieusance, shacking up in an abandoned theater outside of the Villiage, and scavenging the ruins of the nearby cities.  Soon however, they began to be suspected of stealing tools, weapons, and pets from the Villiage.

Most recently, the cult has been linked with the disappearance of David Mathers, who's son had fallen in with the cult.  The time has come, and today, Marshall, you head to the theater they call their "Church" to get to the bottom of this.  Upon arriving, your decisions are made for you: The corpse of David Mathers is hung above the door to the theater on hooks.  You grab your gear, just in time for a cultist to step out and meet you.

## First Scripted Event:

- [ ] Done

Player spawns outside the theater, face-to-face with a cultist enemy.  The enemy delivers lines of dialogue and is scripted to run from the player into the theater.  

If the cultist reaches the doors of the theater, all non-savage enemies will be alerted, and replaced with armed variants.  The player can attempt to arrest the cultist, and gets a chance to extract clues to unlock later content, but in the end the cultist will continue to attempt to warn the rest of the cult and must be killed.

## Sneaking In:

- [ ] Done

If the player kills the cultist, enemy AI's will be mostly Condition White.  The Cultists in the main hall will be facing the stage, and will be unarmed.  The Grand Deacon will be on the stage, and a distant, muffled sermon audio track will play from the main hall.  The Horrors will be locked up in the side room for discovery later.  

Sound Blocking Linedefs will keep any shots outside the main hall from waking the Horrors and the cultists in the main hall.  

## Make a Grand Entrance:

- [ ] Done

If, after sneaking in, the player simply walks into the main hall, they trigger a scripted event.  The Grand Deacon is a non-human monster (Pattern: Hell Knight) and it triggers a line of dialogue egging the assebled cultists to attack the player.  All enemies in the main hall are set to Condition Red, with player as the active target.  Infighting is disabled as long as the Grand Deacon is still alive, and cultists get a 2x health boost.

If the player shoots at the Deacon from the seats, an invisible linedef blocks their shots with a particle effect and warbling sound.  

If the player retreats and goes out of sight of the Deacon, an actor mover moves the deacon backstage, and towards the room with the Horrors. (Use actor mover instead of just a teleport in case the player keeps the deacon in sight somehow)

If the player has already killed the Horrors, then the Deacon is encountered in the Horrors' room.  If the player hasn't, then the Deacon is encountered in the hallway outside the Horror's room, with the Horrors moving along with it, shielding the Deacon.  The Horrors don't take damage from the Deacon's attacks, and are positioned between the player and the Deacon.

## Investigate:

-[ ] Done

The player can loop around the back of the theater, and find that the scene shop has an unlocked garage door.  Inside the scene shop, there is an NPC, the stage manager.  The Stage Manager is friendly, provides testimony about the cult's doings, informs the player about the horrors,  the Hostages, the cult's weapon cache, and gives a stage manager's key. The Stage Manager's key gives access to the backstage hallway doors, the stage access doors, and the ticket booth.  

To the right of the main enterance, there is a ticket booth. In the ticket booth, there is a cultist who is facing away from the ticket window.  This Cultist will wake up if the player fires a shot in the entryway.  If it wakes up, it will take shots at the player, and if wounded it will start heading to the Main Hall. If it reaches the Main Hall, the same sequence as the Grand Entrance path plays out.  When killed, this cultist drops the Cultist Key.  The Cultist Key opens the weapon cache, the Hostage Room, and the room with the Horrors.  On the desk in the ticket booth, there is evidence: A scale and gold prills, and financial documents.  Behind the door to the Ticket Booth, there's an in-wall safe, which has a cache of stolen and collected treasure.

To the Left of the main enterance, there is the cult's Armory. If the script for the alert from the initial cultist has been triggered, then the armory is mostly emptied. Otherwise: the armory contains several pistol and shotgun pickups, (adding up to enough ammo to fill pistol and shotgun capacity.) Green body armor, and medkits.  In the back corner, there's a table with evidence: occult stuff, and a custom weapon: The Caster.   

On the right-side hallway, there are three rooms: An office, a meeting room converted to a hostage room, and a corpse room containing horrors.

The Office has a desk and file cabinets.  There's evidence: Documents on the desk, and occult stuff in the cabinets.  
