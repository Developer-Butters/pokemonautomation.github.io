# Autostory

# Program Description

This program will automate the Brilliant Diamond/Shining Pearl story, from choosing your starter through defeating the Champion.

The program has two sections: the tutorial and the main story. After finishing the tutorial, it will stop at the Pokémon Center PC in Jubilife City. For the outside-help route, you will then use Pokémon HOME to train your starter to level 100 in another game and return it before starting the main story. This allows the program to focus on completing the story without needing to train the team along the way.

## Settings

**Switch Settings:**

1. Screen size: Must be 100% within the Switch settings.
2. System Time: Unsynced. The program changes the time during some routes to control lighting and time-dependent NPCs.
3. [Switch 2: All HDR options must be disabled.](../NintendoSwitch/Switch2Notes.md#switch-2-hdr-may-be-problematic)
4. [Switch 2: The profile you are using must be the first, left-most profile.](../NintendoSwitch/Switch2Notes.md#resetting-a-game-moves-the-cursor-to-the-1st-user-profile)

**Program Settings:**

1. Video Resolution: 1080p or higher.
2. Complete the [computer-control setup](../../SetupGuide/index.md) and select **Pokemon BDSP → Auto Story**.

**Game Settings:**

These will be set automatically during the tutorial. If starting later in the story, check them before running the program.

- Text Speed: Fast
- Change Window: Type 1
- Battle Effects: Off
- Battle Style: Set
- Send to Boxes: Automatic
- Give Nicknames: Don't Give
- Gyroscope: Use
- Autosave: Off
- Show Nicknames: Show
- Background Music and Sound Effects: 8

# Team setup instructions for the main story

For the outside-help route, use the starter obtained on the Autostory save file. Train and evolve that same Pokémon through HOME, then return it to its original save so that it will obey you regardless of your badge count.

Your starter should be fully evolved, level 100 and have the IV/EV spread listed below (use hyper-training and vitamins). When it returns to BDSP, place it in the first party slot and box the other pokemon in the first slot of box one. This is important for later in the story.


## Torterra

| Stat | IV target | EVs |
|---|---|---|
| HP | 31 | 4 |
| Attack | 31 | 252 |
| Defense | 31 | 0 |
| Special Attack | Any | 0 |
| Special Defense | 31 | 0 |
| Speed | 31 | 252 |

**Moves, in slot order:**

1. Crunch
2. Seed Bomb
3. Earthquake
4. Razor Leaf

## Infernape

| Stat | IV target | EVs |
|---|---|---|
| HP | 31 | 4 |
| Attack | 31 | 252 |
| Defense | 31 | 0 |
| Special Attack | 31 | 252 |
| Special Defense | 31 | 0 |
| Speed | 31 | 0 |

**Moves, in slot order:**

1. Thunder Punch
2. Flamethrower
3. Earthquake
4. Brick Break

## Empoleon

| Stat | IV target | EVs |
|---|---|---|
| HP | 31 | 4 |
| Attack | 31 | 252 |
| Defense | 31 | 0 |
| Special Attack | 31 | 252 |
| Special Defense | 31 | 0 |
| Speed | 31 | 0 |

**Moves, in slot order:**

1. Drill Peck
2. Ice Beam
3. Surf
4. Metal Claw

### How to prepare the starter

1. After the tutorial, deposit your starter in the PC. Keep the second Pokémon caught during the tutorial in your party.
2. Save and close BDSP, then use Pokémon HOME to transfer the starter to a compatible game where you can train it.
3. Raise it to level 100 and evolve it fully. Give EXP Candy in stages so that both evolutions can occur. Prepare the IV/EV spread listed for your starter above, correcting any EVs already gained during the tutorial before completing its training.
4. Teach the moves listed above in the specified slot order.
5. Transfer the Pokémon back through HOME. Check the destination-game moves before saving the transfer, and verify the move order again in BDSP.
6. Put the starter in the first party slot and restore its HP.
7. Deposit the extra Pokémon in **Box 1, slot 1** (the top-left slot). It must not be fainted. Leave **Box 1** selected so the program can withdraw it for required double battles.
8. Return to the Jubilife Pokémon Center PC position where the tutorial ended, then select **Main Story**.

# Options

## Story Section

- **Tutorial:** From the player's bedroom after the opening television scene to the Pokémon Center PC in Jubilife City. Start with menus and dialogue closed.
- **Main Story:** From the Jubilife PC after team preparation through the Elite Four and Champion.

The program stops between the two sections so that you can prepare your team.

## Start Point

Start the program at the selected segment. Match the location and facing direction shown in its **Start** description.

## End Point

Stop after completing the selected segment. The **End** description shows where the player will finish.

## Advanced mode

Select individual checkpoints instead of whole segments. This lets you run a smaller section of the story or resume from a checkpoint. Both the selected start and end checkpoints are included.

## Starter Pokemon

Choose **Turtwig**, **Chimchar**, or **Piplup** to match the starter selected on your save file.

## Help Mode

- **Outside Help:** Use a starter trained in another game through HOME, following the team setup above. Use the Starter Pokemon selection that matches your starter and arrange its moves in the order listed above.
- **No Outside Help:** Play without transferring your team to another game for training.

## Notifications

Configure status updates, completion messages, and error notifications through the [Discord integration settings](../../DiscordIntegration/index.md).

# Credits

- **Development:** developer-butters
- **Contributors:**
    - ArceusMI
    - Boombaastical
    - GumGum_Dragoon
- **Framework:** Pokémon Automation contributors.
- **Guide structure:** Based on the [Scarlet/Violet Autostory guide](../PokemonSV/AutoStory.md).

<hr>

**Discord Server:**

[<img src="https://canary.discordapp.com/api/guilds/695809740428673034/widget.png?style=banner2">](https://discord.gg/cQ4gWxN)
