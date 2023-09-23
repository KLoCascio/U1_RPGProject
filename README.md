# U1_RPGProject
Unit 1 RPG Project: API, JS, HTML, CSS

Game Play
1. Turn based style game play.


End Game Conditions
1. (GOOD) Defeat Final Boss
2. (GOOD) Hidden Item-Linked Ending (STRETCH)
3. (BAD) Health hits zero.

-Turn Logic-
(COMBAT): 
1. Player starts turn (odd turns). selects [Attack], [Cast], [Items]
2. [Attack] Input Sequence Will Appear: Deals single target damage. NPC icon will shake. 
   // [Cast] Input Sequence Will Appear: Deals area damage. NPC icons will shake. || (Heal) Input sequence Will Appear: Restores HP of Player. Player Icon will shake.
     // Spell(s): Chosen at Start (STRETCH: Buy and Equip at Merchant). Ice Shards (Water), Fireball (Fire), Boulder (Earth), Lightning Bolt (Air), and Heal.
   // [Items] No Input Sequence Will Appear: Item Effect Depends on Item. Player Icon will shake.
     // Merchant-Buyable Item(s): Potion (+50% HP), Ether (+50% MP), Teapot (Secret Ending Item)
     // Item(s): Sword and Shield (+1ATK +1HP), Wand (+1ATK ?only on Spells, Heal will have an "ATK value" but only target self?), Dual-Wield Daggers (+2ATK (STRETCH: +3ATK on 1st Turn?), Great Sword (+2ATK)
3. NPC second turn (even turns). Attack (+1ATK, Special Ability (+2ATK, offensive or heal), (STRETCH: Defend, takes less damage next turn).

-Scenes-
(INTRODUCTION): //CAMPFIRE BACKGROUND//
1. Options: [A. ROGUE], [B. PALADIN], [C. WIZARD]
2. Enter [Name:__________]
3. "Begin Journey" Button if Step 1 and Step 2 are complete.
4. Always leads to "FORK IN THE ROAD" Scene.

(FORK IN THE ROAD): //FORK BACKGROUND//
1. PC on screen.
2. Options: [Left], [Right]
3. Caption Type: Dialogue, Introduction to story.
4. Always leads to "INTRODUCTION BATTLE" Scene.

(INTRODUCTION BATTLE): //COMBAT1 BACKGROUND//
1. PC on right side of screen. Monster on left side of the screen.
2. Caption Type: (Battle Mode)
   Left- "{PC/Monster} {action}, and {PC/Monster} took {damage} damage. EXAMPLE. {Kyndal} {casts Fireball}, and {Goblin} took {?formula: pcAtkValue + weaponAtk - monDefValue? = 5} points of damage.
   Right- Options: [Attack], *[Cast], [Items] *[Cast] is only available if a spell is learned.
3. Take turns attacking.
4. At end, rewards item(s) and money.
5. Always leads to "MULTIPLE MONSTER BATTLE" Scene.

(MULTIPLE MONSTER BATTLE): //COMBAT1 BACKGROUND//
1. PC on right side of screen. 2 MonsterS on left side of the screen.
2. Caption Type: (Battle Mode)
   Left- "{PC/Monster} {action}, and {PC/Monster} took {damage} damage. EXAMPLE. {Kyndal} {casts Fireball}, and {Goblin} took {?formula: pcAtkValue + weaponAtk - monDefValue? = 5} points of damage.
   Right- Options: [Attack], *[Cast], [Items] *[Cast] is only available if a spell is learned.
3. Take turns attacking.
4. At end, rewards item(s) and money.
5. Leads to either: A. Rest = "CAMPFIRE SCENE" Scene, B. Continue = "GROUP MONSTER BATTLE" Scene

(CAMPFIRE): //CAMPFIRE BACKGROUND//
1. Contains PC, and a Merchant.
2. Caption Type: Dialogue, and Options: [Sleep], [Merchant] or 
3. Happens twice. Leads to either: A. [Merchant] "MERCHANT" Scene B. [Sleep] "GROUP MONSTER BATTLE" Scene

(MERCHANT): //MERCHANT BACKGROUND//
1. Merchant behind a desk.
2. Caption Type: Dialogue, General Greeting and Options: [Buy], [Sell] (STRETCH), [Help] and [Leave]
4. [Buy] List of items to buy.
    // Merchant-Buyable Item(s): Potion (+50% HP), Ether (+50% MP), Fishing Rod, Torch, Item.
   [Sell] (STRETCH) Sell items
   [Help] Leads to "MERCHANT HELP" Scene
   [Leave] Leads to "CAMPFIRE" Scene

(MERCHANT HELP): // BACKGROUND//
1. Merchant on the left. Puzzle/Riddle Scene.
2. Options: [Solve], and [Leave]
3. [Solve] Attempt the puzzle or riddle.
4. [Leave] Leads to "MERCHANT" Scene.

(TRAVEL): (start with 5 scenes, (STRETCH): 10 scenes)
1. (TRAVEL):Fork on a road, go left or right. (Illusion of choice, both go to scene 2.
2. (COMBAT): Attacked by a monster. Maybe easier sequence?
3. 
   


(TRAVEL):
(CHAT):
