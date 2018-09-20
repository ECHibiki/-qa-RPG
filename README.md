# /qa/ RPG

Pastebin done by qanon643735, edited by ECH https://pastebin.com/BSkWbtgG
\
\
game dev discussion: rizon #qa\
 \
volunteer distribution (<Vacant> means no one has taken it)\
programming: ECHibiki\
organizing: ECHibiki\
music: Possibly ECHibiki otherwise <Vacant>\
sprite work: <Vacant>\
level designers: J_\
enemy designers: <Vacant>\
character/class designers: neo\
idea guys: /qa/\
\
========== ECH ==========\
\
__Core_mecanics__\
Some things need to be worked out before I can write up a test program\
\
Programmer Art: \
https://opengameart.org/ \
http://www.derekyu.com/tigs/assemblee/ \
http://pousse.rapiere.free.fr/tome/ \
http://www.dumbmanex.com/bynd_freestuff.html \
https://www.deviantart.com/7soul1/art/420-Pixel-Art-Icons-for-RPG-129892453 \
https://game-icons.net/ \
https://itch.io/game-assets/free/tag-pixel-art \

Characters(Neo has more details if current system is boring):\
- Characters are based on main classes that get promotions into new classes.
- Characters get promotion points on leveling up.
- Promotions effect the skills, stats and have the possibility to redefine a class.
- Promotions are done on a tree.
- Respecs are possible
- Inventory is not weighted(no overburdened)
- Just infinite capacity(A diablo2 row system is out of scope for this project)
- At the moment a 5 stat system[str, con, dex, int, wis]
- Str decides armour which gives a defence stat. 
- Con decides Hp
- Wis is mana
- Stats influence weapon choices

Combat:
- Realtime attack on a timer
- Fighters have skills they bring into combat
- Victory gives you experience
?Victory gives you items?
?How do stats work in combat?
?How do enemies work in combat?
\
Overworld:
- Players traverse dungeons with a team
- Tile movement
- Overhead sprites
- Inventory and equip selection screen
- Rooms
- Players are drawn into combat sequences with allies if they are nearby to the character fighting
- Maps have pitfalls(trigger first time, if open set fall prompt)
- Tidal system(players damaged in high tide) maybe with lava where some squares are safe
- Loot boxes

=========== qanon643735(Restructuring and editing by ECH) ==========

Mechanics: \
real time final fantasy combat\
Players drawn into combat based on proximity to a character in the map \
\
choosable maps \
online play RPG game\
1-6 players per game\
players perform a lobby based objective(as apposed to open world)\
characters have skill trees they dump points into it\
PvP is a consideration\
 \
lobbies set up as hubs that can house more people than a dungeon\
hubs allow you to craft, equip, upgrade, discussion and pre-dungeon role planning\
no branching\
\
\
base classes: \
questioner,brawler,page,mage,warbler,massage therapist,chucker/pelter/stone thrower\
 \
list of classes: \
thief, knight, rogue, bard, seer, mage, page, witch, spy, scout, pirate, ninja, samurai, barbarian, sorcerer, druid, monk, cleric, wizard, assassin, magician, templar, gypsy, shaman, seer, healer, artificer, clown, necromancer, swordmaster, sniper, archer, swordmaster, runemaster, psionic, shade\
/qa/ derived classes: spammer, banana knight, questioner, ghost, filterer, bump-bot, blogger, meta, roleplayer\
 \
(aspect allows further customization to a class, can give passive/active class/aspect abilities)\
aspect: explosion, life, fire, fear, blood, shadow, faith, hope, earth, rage, air, water, time, light, illusion, sun, thunder\
 \
class upgrade tree in addition to skills tree\
buy generic skills\
new class abilities/skills (whatever you want to call them)\
appropriate stat boosts\
other class appropriate stuff\
 \
a set of skills that get replaced every class change along with stats\
base class has a set of skills\
you upgrade to add onto those skills\
when you upgrade again you get a new set of stronger skills\
 \
Characters:\
Characters are based on main classes that get promotions into new classes.\
Characters get promotion points on leveling up.\
Promotions effect the skills, stats and have the possibility to redefine a class.\
Promotions are done on a tree.\
Respecs are possible\
 
Combat:\
Realtime attack on a timer\
Fighters have skills they bring into combat\
Victory gives you experience\
 \
Overworld:\
Players traverse dungeons with a team\
Players are drawn into combat sequences with allies if they are nearby to the character fighting\
 \
Strength, constitution(maybe simplify this to HP), dexterity, intelligence and wisdom should be enough[str, con, dex, int, wis] to determine whether item can be equipped\
a smaller set of stats that are changeable on level up and then ones like movement, defense, perception et. al. can be shown but they're calculated from the smaller set of stats.\
charisma can be incorporated in to fighting, using it for intimidation moves or trying to convince enemies to fight with the party and so forth could add some cool angles to encounters.\
 \
skill suggestions:\
Rape soul - visit the timeline where you and the targeted creature fall in love and have children, kidnap one child and brainwash it into fighting its parent (just a dark summon with debuffs I guess?)\
Go back there - haunt the targeted creature with vivid memories of its childhood, paralyzing it with homesickness for a few turns\
Postprecognition - reduce damage dealt to you in the previous turn and strengthen against that type of attack (heal+buff)\
Prepostcognition - the next attack against you will deal 1.5x nonfatal damage and buff the next spell you cast\
Charge rent - call upon one of your other personalities to perform a massive attack, they'll be angry with you after (big attack and self-debuff to int/wis)\
Bump thread(or something, idk) - make targeted creature unreasonably angry, attacking randomly for reduced damage\
\
\
Possible ideas:\
tiered items like healing items\
discoverable weaknesses on enemies\
moves with limited uses\
team management a part of combat, buffing a friend vs attacking\
some randomness in moves, stat-dependent crits, weapon-dependent extra damage\
  
levels=threads, with rolling stickies, greentext walls, (you) bombing, (you) farming\
cyberpunk, generic fantasy or /qa/ themes\
one player character as the party leader and map avatar\
 \
difficulty scaled by party size and a little bit by subgroup size\
subgroups composed of nearby party members\
3 seconds to join on encounter\
