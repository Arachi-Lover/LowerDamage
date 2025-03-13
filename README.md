# LowerDamage

This plugin rescales the damage of weapons throughout Endless Sky in order to make the game's combat slower, and also aid in making ships affected by LinearHPScaling last longer in combat (though this plugin may be used on its own just as well).

The idea was to multiply the damage of every weapon in the game by a decimal factor, in order to make combat feel slower, with ships lasting longer and regeneration mattering more.

These multipliers would apply only to damage values that affect shields and hull, be that per shot/hit or over time, as a means to also give more value to the status effect damage types. Thus, the affected damage types are:

- shield
- hull
- discharge
- corrosion

Spacefaring creatures such as the Void Sprite and Subsidurial were not affected.

Below are the multiplier values across Tiers, and some notes specific to some outfits/groups.

```
T1 and below
	* 0.7 damage
	(The Nuclear Missile remains unchanged, as it should continue to pose a very credible threat to human ships over the campaign, and by consequence of all other weapons being weaker, would also become a more considerable reward for picking the Checkmate branch)
	(Of the Sheragi, only the Dragonflame Cannon was altered, as the turrets aren't particularly great as is, and also owing to the unique nature of the reward-ship and its Fighters)
T1.5
	* 0.75 damage
T2
	* 0.8 damage
T2.5
	* 0.85 damage
	(The MCS Extractor was spared for it already is terrible at dealing damage)
T3
	* 0.9 damage
T4
	* 0.6 damage
	(Only the Drak Augmented weapons were affected)
```
