Gaige Anarchy Rework
====================

The goal of this mod is to make stacking anarchy much faster so you can focus on playing the game and killing things instead of reloading in a corner for 10 minutes.
Other mods try to solve this by giving all the stacks through Rational Anarchist, but what's the point of stacks by that point?

This mod attempts to resolve this by *reducing* the number of max stacks by 5x (including Preshrunk and Rational Anarchist) and *increasing* all anarchy effects by 5x (including Anarchy, Discord, Death From Above, and With Claws): same overall power, faster acquisition.
Discord, in particular, is much stronger in the short term due to the stat bump, but much more of a trade-off because of fewer max stacks (example: faster healing, but same total healing).

The only other change I made was bumping the *relative* value of Rational Anarchist up by 3x (in this case: 5 stacks to 15 stacks). 
Because getting damage from stacks is so much quicker, the small initial bump provided by this skill had much less value, only saving you from having to get 5 kills + reloads (even less with typecast).
Since I still want the skill to have value and not be skipped in the tree, I gave it a decent bump to keep it relevant. 

With this mod, you can now enjoy gaining anarchy stacks naturally by playing the game and killing things, while also saving time when you do want to pre-stack.

Math Example:
---------
New Anarchy:

Max stacks = 30

Damage per stack = 8.75%

Total damage = 30 * 8.75% = 262.5%

vs

Old Anarchy:

Max stacks = 150

Damage per stack = 1.75%

Total damage = 150 * 1.75% = 262.5%


Install
=======

Install like any other BLCM mod (File -> Import single mod).

Everything in the mod is sectioned off by skill if you want to make your own adjustments.

If you want to use UCP along with this, make sure to disable the With Claws changes. I integrated the With Claws changes from UCP and multiplied the effects because I also like running UCP (obviously, credit to the UCP team for those changes). 

I didn't touch the added healing UCP gave to this skill, but the damage and swap speed are scaled to the new values (didn't need more healing when testing).

Changelog
=========

**v1.0.1**, May 12, 2025:
 - Buffed Death From Above damage to match stack scaling (forgot about that skill lol)
 - Increased Rational from 10 to 15 stacks

**v1.0.0**, May 12, 2025:
 * Initial release
