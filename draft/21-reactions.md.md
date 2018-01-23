## Reactions
Return to the Wild West. There are two players forty paces apart facing each other. One of them takes their neckerchief off and throws it high into the air. The first to press the trigger on their controller, after the neckerchief touches the ground, wins. This is a reaction game.

> **Reactions**:  gaining a competitive advantage by having faster reactions than your opponent.

Reaction tests are often combined with other traits to make interesting games e.g. sprinting (w/ speed) and jungle speed (w/ pattern matching).

> **Reactions**:  gaining a competitive advantage by having faster reactions than your opponent.

### Reflexes
It's important to mention reflexes at this point. It is easyWhen talking to other people about reactions we seem to confuse reflexes and reactions. Both a fast responses from our body, but there is a difference between the two.

Reflexes are the *unconscious* reactions of your body to a stimulus. The patellar reflex, or knee-jerk, of your leg kicking when your knee is tapped in the correct spot is an example of an unconscious response from our body. As they are unconscious they are of little interest to game design.

### Stimulus
We are going to talk about three types of stimulus or cue that are used to trigger a reaction test. Seeing the cue (vision), hearing the cue and feeling the cue (tactile).

In the *100m Sprint* it's the sound of the starter's pistol that sets the runners off. In *Duck Duck Goose*, the touch on the head starts the chase and in *Jungle Speed* it's seeing a matching pair of symbols that starts the violent grab for the token.

Humans react to different stimulus at different speeds. Audible cues are reacted to fastest, then vision and finally tactile. This is important when adding these elements to your game. As you make your reaction tests harder your players will need to rely on audio cues more and more.

## Difficulty Vectors
Each difficulty vector represents a single dimension we can tweak to increase or decrease difficulty. There are two vectors that relate solely to reaction:

- maximum time
- minimum time

And there are a few vectors from other traits that intermix well with reaction:

- cue prominence (hearing, vision, tactile)
- decisions (choice)
- duration (stamina)
- speed (speed)

### Maximum Time
We can make reaction games harder by slowly reducing the amount of time the player has before they must respond. If they take too long they automatically fail.

This is a very common aspect of endless runner games. Take a look at Temple Run, Super Hexagon and Canabalt. All three of them require the player to react within a certain time period. If you wait too long then you lose.

{<1>}![Super Hexagon requires you to react quickly before it becomes too late.](https://lh4.ggpht.com/pdxaqhQmHdXWjRdiRz4dIpjiTgwGz4AeRnHb3Raw6cnVMcbSHy5PUkGHsxCOsmRJs6Q=h900)


Temple Run implements maximum time in two ways. The first is like most endless runners in that the game speeds up as you play. The second way is in the left and right changes of direction. As the player cannot see what is around the corner they cannot prepare for what is coming. When they’re finally shown what is around the corner they only have a limited time to react.

Another example is Canabalt that reduces the *maximum time* you have by going faster. The game then also gives you the option of crashing into boxes and *wiping off speed*. This increases the *maximum time* you have to react. All this being said, it can also leave you without enough speed to make the next jump.

### Minimum Time
Maximum time challenges require the player to react within some time period. The *minimum time* restriction penalises players who react too quickly or who are trigger happy.

Taking a look at Canabalt again. This game occasionally employs this tactic through the use of windows. The windows require the player to wait longer than usual before reacting.

{<2>}![/canabalt-window.png](Canabalt - The player has to wait a minimum time before jumping through the window.)

An important element of the *minimum time* difficulty vector is providing a cue to the player about how close they are. In the *Canabalt* screenshot we can see that the player near the window. The closer they are to the window the closer they are to having successfully waited for the minimum time.

Later I talk about the various modes for the *Challenge:Response* game. Two of these modes show off the minimum time with and without a cue to tell you when the time has passed.

### Cue Prominence
This difficulty vector is really the interplay between *reaction* and another trait that can provide the stimulus. These being *hearing*, *vision* and *tactile*. I recommend you read those sections to get the most of them. I'll cover just the interplay here.

By altering how easy it is for the player to identify the cue, the faster they will be able to react. It's worth remembering that different stimulus will result in faster or slower reaction times.

#### Vision: Size
When the cue is visible, then the size of the cue determines how quickly you see and react to the change. A tiny cue of a single pixel is going to be harder to spot than a cue that consumes the entire screen.

By making the cue smaller over the course of the game, the game will become harder.

#### Vision: Contrast & Colour
TODO: write this bit. It’s similar to above

#### Vision: Position
When the player knows where the cue is going to be they can focus all their attention on that spot waiting for the change. If the position changes randomly then the player can't focus their attention as well.

A fixed cue position is the easiest. Small variations in the placement of the cue increase the difficulty slightly. By having the cue placement jump randomly with a minimum distance between each jump will make a much more difficult challenge.

The cue size relates to the difficulty. A large cue is harder to move around than a small one.

#### Hearing: Volume
The loudness of the audio cue is the equivalent of the size of a visual cue. Therefore quieter cues are going to be harder for the player than loud cues.

Hearing tests, the ones that are used to determine how good your hearing is, use quietness to determine whether your ears are damaged. Hearing tests are interesting because you they could play no sound, to catch you lying, and you wouldn't be able to tell.

#### Hearing: Direction
The direction, for most people this is left or right channels only, can be used as a cue. By itself the difference in the cue will make little difference to the reaction times of the player. This is because audio cues are reacted to very quickly by our body.

To make this a more useful difficulty vector we can couple this with the *recognition* difficulty vector of the *choice* trait. If the player is supposed to react to the left channel and not the right channel then it becomes harder.

This trait can also be combined with *discrimination* where the player is required to hold a key based on how far to the left or right the sound is.

#### Tactile: Pressure
The pressure of the sensation is the equivalent of the size of a visual cue, or the loudness of an audio cue. Therefore softer pressures are going to be harder for the player than stronger pressures.

There isn't a wide range of pressures available to mobile devices and controllers. So you should probably avoid using the solely as a cue.

In physical games this is also a challenge as there is no agreed upon definition of pressure between players. What is weak for one player may be too strong for another.

#### Tactile: Direction
The tactile direction is the equivalent of the hearing direction. Like tactile pressure there is limited directional support in controllers and mobile devices. The player really needs to have something in each hand.

This can work in physical games where depending on whether you get touched on the left or right side, you react.

Like hearing direction, this difficulty vector can be combined with the *choice* trait vectors of *recognition* and *discrimination*.

### Decisions
*Choice* is a *mental* trait and is covered later in this book. Having to choose directly influences reaction time. Here we'll talk about the interplay of these two traits and the stimulus related traits of *vision*, *hearing*, and *tactile*.

For the stimulus this could be represented by different visual shapes, different sounds or different pressure patterns (a tap, a slap, a shake).

The simplest approach is not having to make a decision. This is the standard reaction test. I react when I see the stimulus. In, Temple Run, I jump when I see the chasm. There is no decision to be made, it's a question of whether I react fast enough.

#### Recognition
The next approach is *recognition*. This is where you have a go/no-go decision to make. This is another name for combining *noise* in the cue and *reaction*. In *Duck Hunt* if the player accidentally shoots a dog they lose immediately. The dog is noise. The player's reactions are slowed by the decision to shoot or not.

#### Choice
After *recognition* comes *choice*. Here there are multiple cues and each cue requires a different response. Think of *Temple Run*. In that game you have the option to: *turn*, *jump*, *lean*, *slide*. Each of the these has a cue. When you see the correct cue, make the correct move.

#### Discrimination
The last mode is *discrimination*: This is the same as combining *fidelity* in the cue and *reactions*. Instead of having to jump when they see the cue the player has to determine how far they need to jump. Do they hop, jump or go for a long jump. This can be seen in most platform games.

### Duration
When you mix *reaction* with *stamina* you end up with Endless Runner games. The differentiator between players in these games is the players who can maintain their reaction ability for the longest period of time.

### Speed
Your standard Endless Runner game gives the player a window within which to react. They are not about being the fastest player to react. The wild west scene I painted at the start of this section is about who reacts the fastest. The game of *Jungle Speed* is another game where the fastest to react wins. This is of course, after they've completed the *Pattern Matching* challenge.

When you mix *reaction* with *speed* you get challenges where only the fastest reacting player wins.

## Example Games
### Challenge-Response
The Challenge-Response game has been devised to test a players reaction skills. I've tried to move the influence of *coordination* from this game. So prepare to mash that spacebar, mouse or touch-display.

> **TODO: format this as QR codes and URLS that launch the game in the browser or on the phone.**

- Minimum Time
- Minimum Time with Cue
- Maximum Time (3 levels @ 1000, 500, 250)
- Cue Prominence Visual (tiny, large, static, dynamic)
- Cue Prominence Hearing (left, right, quiet, loud)
- Cue Prominence Tactile (left, right, weak, strong)
- Audio Only
- Vision Only
- Tactile Only
- Recognition (visual, audio, tactile)
- Choice (visual, audio, tactile)
- Discrimination (visual, audio, tactile)
- Duration (8 Seconds)
- Speed (Quick Draw)

### Irrelevant
*Chess* - Being able to react more quickly to the other's players moves will not improve your ability to win.

### Relevant
*Sprinting* - The difference between the first and sixth place in the 100 metre sprint final of the 2012 Olympics was 301ms. The athletes from those all races had a median reaction time of 166ms and one runner had a reaction time of 118ms[1](http://www.plosone.org/article/info%3Adoi%2F10.1371%2Fjournal.pone.0026141). With the slowest at 322ms this makes a difference of 204ms. In a race about being the fastest, your reaction time may be enough to help you win against an equally matched opponent.

*Quick Time Events* - Many computer games during the 2000's featured QTEs. These require the player to press a specific button a keyboard within a time period. If the QTE influences the outcome of the game, then it's relevant. If it doesn't influence the outcome, don't include it in the game.

### Vital
*Endless Runners* - Canabalt, Temple Run, Super Hexagon - All these games test your reaction trait.

*Jungle Speed* - In this game, When the same pattern (ignoring colour) is placed on the table than the player with the fastest reactions to recognise the pattern and grab the token off the table wins the exchange. That player moves their discards to the other player.

*Lightning Reaction* - In this game each player holds a controller. When the sound goes off, the last to press their trigger will get shocked.
