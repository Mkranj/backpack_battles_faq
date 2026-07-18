# Backpack Battles Interactions FAQ  
This is a list of general questions players of Backpack Battles may have regarding specific interactions that are somewhat obscure or vaguely worded. Browse through the main categories or use Ctrl+F to search for item names, keywords etc.  

Add more questions and answer by opening a PR to this repository! Help the community out by making this information more easily available. Also feel free to contact me if some answers are wrong or changed in updates.  

**Game version** at time of writing: 1.1.7  

## General mechanics  

### What is the difference between an item triggering and activating?  
E.g. [Goobert](https://backpackbattles.wiki.gg/wiki/Goobert) counts 5 item activations. [Jynx torquilla](https://backpackbattles.wiki.gg/wiki/Jynx_torquilla) makes items trigger 5% faster.  
**Answer:** These terms are used interchangeably. If an item has **On hit:** text, hitting an opponent (but not missing!) is a trigger and an activation of that item. A weapon has a cooldown of 3s means that it will trigger and activate each 3 seconds. **On battle start:** is a trigger/activation. Notably, **On shop enter:** technically doesn't count as either since it occurs outside of battle.  

### Will gaining Max health permanently increase it across rounds?  
**Answer:** No. Any Max health increase is valid only for the round the effect triggered in.  

### Does stealing buffs count as gaining buffs?  
E.g. [Squirrel](https://backpackbattles.wiki.gg/wiki/Squirrel) steals enemy buffs, while [Paradise Birb](https://backpackbattles.wiki.gg/wiki/Paradise_Birb) has a chance of duplicating buffs an item gains.  
**Answer:** No. Interactions involving gaining buffs only occur if the item explicitly states ***gain*** *X buff*.  

### What does it mean when a crafting recipe has an item with a green background?  
E.g. Crafting recipes for [Holdall](https://backpackbattles.wiki.gg/wiki/Holdall) have these.  
**Answer:** The item with a green background won't be consumed by the crafting. Any other items will be consumed as normal.  

### Does **On stun:** apply when I get stunned, or when the opponent gets stunned?  
**Answer:** The effect triggers when *the opponent* gets stunned.  

### If an effect states **30 buffs: do something** or similar, will that apply only at 30 buffs accumulated, or every 30 buffs?  
E.g. [Manathirst](https://backpackbattles.wiki.gg/wiki/Manathirst) states *30 mana: deal 10 magic damage*.  
**Answer:** The effect triggers *every* 30 buffs you gain. It can proc multiple times.

## Ranger  

### What happens if my critical hit chance exceeds 100%?  
**Answer:** The critical hit chance is capped at 100%. In effect, items behave the same with e.g. 120% critical hit chance as they would with 100%.  


## Reaper 

### Does **[The Lovers](https://backpackbattles.wiki.gg/wiki/The_Lovers)**' "If the number of cards before is even, gain 2 regen" effect occur if it is the first card?  
**Answer:** Yes! Zero cards counts as even for the purpose of this card's effect.  

### Can the reveal time of cards be lowered from 1.5s?  
**Answer:** Yes, effects that affect cooldown apply to card reveal time.  

## Berserker
### Can you enter Battle Rage multiple times during a single battle?  
**Answer:** Yes, with the primary example being [Extra Angy](https://backpackbattles.wiki.gg/wiki/Extra_Angy). If somehow you enter a Battle Rage during an existing Battle Rage, the effects don't stack and the duration becomes the duration of the 2nd Battle Rage. *(untested)*  

