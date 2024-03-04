# Intro level: Investigating the Theater Cult

## Opening Crawl:

The Villiage of Lyndale has been troubled by the emergence of a strange cult, rallying around a demagogue figure they call "The Grand Deacon."  Initially the cult was a mere nieusance, shacking up in an abandoned theater outside of the Villiage, and scavenging the ruins of the nearby cities.  Soon however, they began to be suspected of stealing tools, weapons, and pets from the Villiage.

Most recently, the cult has been linked with the disappearance of David Mathers, who's son had fallen in with the cult.  The time has come, and today, Marshall, you head to the theater they call their "Church" to get to the bottom of this.  Upon arriving, your decisions are made for you: The corpse of David Mathers is hung above the door to the theater on hooks.  You grab your gear, just in time for a cultist to step out and meet you.

## First Scripted Event:

Player spawns outside the theater, face-to-face with a cultist enemy.  The enemy delivers lines of dialogue and is scripted to run from the player into the theater.  

If the cultist reaches the doors of the theater, all non-savage enemies will be alerted, and replaced with armed variants.  The player can attempt to arrest the cultist, and gets a chance to extract clues to unlock later content, but in the end the cultist will continue to attempt to warn the rest of the cult and must be killed.

## Sneaking In:

If the player kills the cultist, enemy AI's will be mostly Condition White.  The Cultists in the main hall will be facing the stage, and will be unarmed.  The Grand Deacon will be on the stage, and a distant, muffled sermon audio track will play from the main hall.  The Horrors will be locked up in the side room for discovery later.  

Sound Blocking Linedefs will keep any shots outside the main hall from waking the Horrors and the cultists in the main hall.  

## Make a Grand Entrance:

If, after sneaking in, the player simply walks into the main hall, they trigger a scripted event.  The Grand Deacon is a non-human monster (Pattern: Hell Knight) and it triggers a line of dialogue egging the assebled cultists to attack the player.  All enemies in the main hall are set to Condition Red, with player as the active target.  Infighting is disabled as long as the Grand Deacon is still alive, and cultists get a 2x health boost.

If the player shoots at the Deacon from the seats, an invisible linedef blocks their shots with a particle effect and warbling sound.  