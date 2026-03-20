# XC2-TAS-BDAT

In the absence of proper multi-game playback tools for Switch TASing, which haven't been developed as of yet, we have mods to help us out until then.

This is an edited common.bdat that simulates perfect RNG in Xenoblade Chronicles 2.

Affected RNG:

- 100% critrate
- Player attacks always land
- Enemy attacks always miss
- Core chips always have highest possible damage value*
- Weapon stability removed*
- Slayer perk has 100% kill chance
- Optimal droprates for Any% Normal DLC (just Puzzletree as of now.)

 *This was done by calculating the maximum possible roll for each core chip and modding out the regular stability. This should work fine, but may have unforeseen issues with the damage formula I may be unaware of, but that is yet to be seen and is unconfirmed as of now.

# Installation

place bdat in romfs -> bdat
