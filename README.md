# U1_RPGProject
Unit 1 RPG Project: API, JS, HTML, CSS

Game Play
1. Turn based style game play.


End Game Conditions
1. (GOOD) Defeat Final Boss
2. (GOOD) Hidden Item-Linked Ending (STRETCH)
3. (BAD) Health hits zero.

Turn Logic
(COMBAT): 
1. Player starts turn (odd turns). selects [Attack], [Cast], [Items]
2. [Attack] Input Sequence Will Appear: Deals single target damage. NPC icon will shake. 
   // [Cast] Input Sequence Will Appear: Deals area damage. NPC icons will shake. || (Heal) Input sequence Will Appear: Restores HP of Player. Player Icon will shake.
     // Spell(s): Chosen at Start (STRETCH: Buy and Equip at Merchant). Ice Shards (Water), Fireball (Fire), Boulder (Earth), Lightning Bolt (Air), and Heal.
   // [Items] No Input Sequence Will Appear: Item Effect Depends on Item. Player Icon will shake.
     // Merchant-Buyable Item(s): Potion (+50% HP), Ether (+50% MP), Teapot (Secret Ending Item)
     // Item(s): Sword and Shield (+1ATK +1HP), Wand (+1ATK ?only on Spells, Heal will have an "ATK value" but only target self?), Dual-Wield Daggers (+2ATK (STRETCH: +3ATK on 1st Turn?), Great Sword (+2ATK)
3. NPC second turn (even turns). Attack (+1ATK, Special Ability (+2ATK, offensive or heal), (STRETCH: Defend, takes less damage next turn).


(MERCHANT):
1. Merchant behind a desk.
2. General Greeting && list of items to buy.
    // Merchant-Buyable Item(s): Potion (+50% HP), Ether (+50% MP), Teapot (Secret Ending Item)

(TRAVEL): (start with 5 scenes, (STRETCH): 10 scenes)
1. (TRAVEL):Fork on a road, go left or right. (Illusion of choice, both go to scene 2.
2. (COMBAT): Attacked by a monster. Maybe easier sequence?
3. 
   


(TRAVEL):
(CHAT):
