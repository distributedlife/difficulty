## Ability to Sustain Damage
A special case of the **resource management** difficulty vectors. This one directly influences the ability for the player to play the game. Without ammunition the game is difficult but there may be a way through. With the loss of health the game is over. 

Unlike the other difficulty vectors this one is a set of values describing game behaviour. This is because most games choose one of these values and stick with it throughout the course of the game. As such I'll call them approaches rather than vectors in this section.

#### Variation: Health System / Damage Model

 - **No Health System / Instakill** (*Super meat boy*)
 - **No health recovery system** (Space Invaders) 
 - **Partial Recovery Health System** (*Left 4 Dead*)
 - **Full Recovery Health System** (*Quake*)
 - **Regeneration** (*Gears of War 2*)
 - **No Damage Model / Invulnerability** (*Dear Esther*)

These approaches are about how much leeway the player has with their mistakes. These are then combined with 

- Time to heal
- When and where healing can take place
- Impact of Health Loss
- Scarcity
- Death Permanence

##### No Health System / Instakill
This approach means that one mistake costs the player their life. Death means the player needs to restart the level or in brutal circumstances, the game.

##### No Health Recovery System 
The player can be hit more than once but the damage cannot be reversed. These games are more forgiving while still valuing health as a precious commodity. 

##### Partial Recovery Health System
This is when the player cannot get all their health back. Left 4 Dead gives the player 80% of the missing health back and there is often not enough health kits to get them to 100%. Once injured the player can never return to full health. This percentage based approach is useful when coupled with scarcity. Infrequent opportunities to apply health means that players are more likely to be low on health when healing. Giving them a percentage back will bring most players back to good health and in line with each other.

##### Full Recovery Health System
In Quake the player can have between 1 and 100 health (ignoring megahealth). A medkit gives 25 health and four kits will restore them to 100. This allow the player to make mistakes and return to full health.

##### Regeneration System
A regeneration system requires the player to not get hit for a while and their health will restore. This is a lenient model as it’s usually easy for the player to stop behind cover and ‘undo’ their mistake.

It also means that the writers don't have to find some reason for health to be strewn about the landscape.

##### No Damage Model / Invulnerability
Health has no influence on the game. This often used for games where the player's ability to survive attacks is not what is being tested here.

#### Variation: time to heal
The models that have a chance to restore some health are again can be split on how quickly is healing applied:

- **Instant Healing** (*Quake*)
- **Instant after Wait** (*Left 4 Dead*)
- **Heal over Time** (*Fallout 4*)

##### Instant Healing
The application of health is instantaneous. This is most early first person shooters where health was placed on the ground, when the player runs over the health they heal.

##### Instant after Wait
The application of health is applied at the end of the healing animation. This requires the player to hold the heal button down until healing is complete; about three seconds . There can be some wonderfully tense moments as you wait for the healing by watching a flood of zombies pour over the rooftop and into the alley where you are.

##### Heal Over Time
The application of the healing is instant but is applied over time. Often the amount of healing you are going to receive is clearly visible and your current health slowly climbs to that mark. Fallout 4 uses this system where munching on some mutfruit will give you a small chunk of potential health. Then over time your actual health increase to reach your potential health.

This approach forces the player to be more careful after the loss of health as they are could easily be killed until they have regenerated. 

The showing of potential health on the health bar is a user-experience tweak to give the player a clear indication that their health has been applied and it will get there soon. This is important in games like *Fallout 4* where the player may need to consume multiple pieces of food to reach their full potential of health. 

Other games like *Divinity Original Sin 2* apply health every *turn* while the healing is in effect without showing the final health target. The player will see a number like +45 appear over the character each turn until the healing has expired or the player is healed. Such games it is not as important to show the potential health because the resources for applying health are not as scarce and the time it takes to heal is much shorter than in a game like *Fallout 4*.

#### Variation: when and where healing can take place

With any approach that supports healing comes the question of when and where healing can take place. 

- **Whenever/Wherever** (*Quake*)
- **Outside of Combat Only / Wherever** (*Rise of the Tomb Raider*)
- **At Specific Locations** (*Quake*) 

##### Whenever/Wherever
As long as the player has some method of applying health, they can apply it.

##### Outside of Combat Only / Wherever
As long as the player is not in combat they can heal. *Rise of the Tomb Raider* does this at the *Seasoned Raider* difficulty level. This forces the player to manage their health during combat and then gives them a breather afterward as their health restores. The next level of difficulty, *Survivor*, disables health regeneration entirely.

##### Whenever / At Specific Locations 
This means that health cannot be taken around. In some cases it's at the start of each level the health of the player is restored e.g. *Space Invaders* which we can contrast to *Missile Command* where the health –manifested as cities, is not restored from level to level.

This approach also applies to games like *Quake* where health cannot be picked up and carried around by the player forcing them to heal when available.

#### Variation: Scarcity
Scarcity of healing locations or health influences difficulty as well. If healing is few and far between then the player needs to be more careful on losing health and more discerning of when is the right time to heal. Scarcity as a variation with a continuous spectrum from *Scarce* to *Abundant*. Either side of this could be perceived as *Non-Existent* or *Ubiquitous* but both of those terms change this variation into something else. If health is non-existent then you have *no health recovery* system and if health is ubiquitous then you have *regeneration* or *no damage model*.

Scarce <---> Abundant

What scarce means will differ from one game to the next and from one difficulty mode to another. 

#### Variation: Impact of Health Loss
- **No Impact** (Quake)
- **Damage Reduces Effectiveness** (*Indianapolis 500*)
- **Damage Increases Effectiveness** (*Fallout 4*)

##### No Impact
It does not matter how low the player's health is, as long as it is above zero then they compete with unchanged effectiveness.

##### Damage Reduces Effectiveness
This is often implemented in racing simulations where the damage the players car takes reduces it’s effectiveness to complete and therefore makes the game harder. The act of fixing the damage, if possible, also costs the player a time penalty that often leaves the player in such a position that they cannot win. The player has to weight up the cost of the damage versus the time lost to restore their car to full health.

In games like *Fallout 4* the damage the player takes may impair some aspect of game play. A shot in the face blurs the screen, a shot in the leg reduces movement speed. 

##### Damage Increases Effectiveness
The variation is either a part of the game or perhaps a feature of one class where the more damaged the player is, or once damaged to a certain extent e.g. 25% health remaining the player is able to dish out more damage. 

The *Nerd Rage* perk in *Fallout 4* works in this way: "*+50% Damage Resistance and Strength is raised to 10 if HP drops below 20%*"

#### Variation: death permanence

- **Game over, no more games can be played / Everlasting Death** (*Upsilon Circuit*)
- **Game over, all progress is lost / Permadeath** (*Spelunky*)
- **Restart level** (*Super Meat Boy*)
- **Restart checkpoint** (*VVVVVV*)
- **Restart at last save** (*Divinity: Original Sin 2*)
- **Rewind the last X seconds** (Prince of Persia: The Sands of Time)

##### Game over, no more games can be played / Everlasting Death
There are only a few games out there with this approach. Once you play the game it cannot be played again. I'm going to consider all games that have this feature but could be circumvented through an understanding of the technology as having everlasting death. In the game *One Chance* you can play it on another platform or clear your browser cache. With *Upsilon Circuit* they used probability to ensure you wouldn't get a second go.

Either way, once you have played the game, that is it.

##### Game over, all progress is lost / Permadeath
When you die, the game is over. You get to start the game again but all progress made on that play through is lost. *Spelunky* although it also has a semi-persistent world where the changes from one run will be present in a second one.

A *permadeath system* should be coupled with a single session playtime or an *Exit Save*.

##### Restart checkpoint
When you die, you restart at the last checkpoint you crossed. This can be within a level *VVVVVV* or once for each level *Spelunky*. Games that have *instakill* tend to have death permanence oriented around levels. See the section on *save and checkpoint scarcity* on how changing the distance between checkpoints or saves. 

##### Restart at last save
Saves tend to push the control of when to checkpoint into the hands of the player. This could be done through quick-save that lets the player save at any point or, through a system like sleeping in *Fallout 4 - Survival mode* where saves will only be made when the player sleeps.

##### Rewind the last X seconds
> TODO: this bit

#### Variation: save / checkpoint scarcity
Just as health is scarce, save points can be too, whether through checkpoints or save mechanics. This drives up difficulty for the player as the pressure increases as they become more invested in the playthrough and closer to the next checkpoint. 

One way to measure scarcity is in time. If a level takes five minutes to complete it has the same scarcity as a longer level that has sub-level checkpoints roughly five minutes apart.

Scarce <---> Abundant

A save system where the player can press F5 whenever they want has abundant saves. A save system that only saves when the player can find a bed, that's scarcity.


### Sticking to it 

Now, I said that most games pick a model and stick with it. The difficulty vector is how much health (resource) is available and the damage (loss) caused by a mistake. These are resource management vectors and covered separately to here.

It is possible for a game to change models and use the changing of the model to represent the changing difficulty. The player could start with a regeneration model and then through narrative it breaks and a full health model is brought into play. Over time the effectiveness of health kits is reduced and the player gets less and less of a benefit from them. The game progresses with the introduction of mechanics that result in damage to the player reduces their effectiveness (be it to fight back or to move) and finally the player is left in a situation where touch is death. This last model should be reserved for the end game. Here no other aspect of the game is made more difficult except the changing of the damage model. Here we find out how well the player can manage their health resource and triumph.

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTEwNDM3NzUwNV19
-->