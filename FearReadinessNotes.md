# Fear and Readiness System

Shamelessly based on the video by Ryan McBeth

## Readiness
- White:
- - Will not react to player on sight
- - 5 sec delay reaction on taking damage, go to Orange
- Yellow:
- - 2 sec delay on sight
- - go to orange on taking damage
- Orange:
- - Standard doom idle state
- Red: 
- - Combat AI state
- Black:
- - Todo

## Fear States

Fortitude 0-20
Varies by character, also subject to bonuses and debuffs.

- Fight Fortitude: 16-20
- - Standard Doom AI, will charge the player and attack
- Posture Fortitude: 10-15
- - Will seek cover, attack player at distance.
- Flight Fortitude: 5-9
- - Will flee to next area or nearest comrade, Raises Readiness of next area, Will seek cover, attacks player at distance.
- Submit Fortitude: 0-4
- - Will seek cover, Will not attack player, can be arrested in this state

### Bonuses:
- In sight of leader: +2
- within 64 MU of another enemy: +2
- Player under 50 health: +1
- Bolster Spell: +4
- Frenzy Spell: Make enemy savage

### Debuffs:
- No other enemies in sight: -2
- Wounded < %50: -2
- Wounded > %50: -2 additional
- Within 64 MU of another enemy when killed: -2 for 30 sec
- Fear Spell: -4



Savage Character: 20 fortitude, not subject to debuffs
Leader Character: 17-19 Fortitude, not subject to wounding debuff
