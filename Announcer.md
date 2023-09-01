# Create your own announcer

## Prerequisites
* Any audio editor - e. g. Audacity or Audition
* Announcer sound source - either your beautiful voice or memes cut etc
* Text editor (Notepad is enough)
* Move or Die copy

## How-to

1. Create an [empty mod](./ModStructure.md).
2. Make following folder tree inside the mod directory: `Lib/Sound/Announcer/<your announcer name>/`.
3. In the `<your announcer name>` folder add audio files (*lines*) for your announcer.
4. Restart Move or Die, then enable your mod and select your announcer in audio settings.
5. (optional) [Publish your announcer mod](./PublishMod.md).

## Notes
* All files **must** be in OGG Vorbis format. There are no file extensions for the part below, but keep in mind that these must still be `.ogg` files.
* You **can do multiple different (or not) phrases per line** - just add a number to the end of file name (e. g. `game@draw.ogg`, `game@draw_2.ogg`). They will play randomly in game.
* Pay attention to the **"mistery" lines**. If you don't know how to announce the line, skip it, and random "mistery" line will play instead (that's also applicable to new or custom game modes). But also do not abuse skipping lines! This can lead, although amusing, to unnecessary situations (since "mistery" lines are very general).

## Example lines

### General

> *Lines for specific situations. These play throughout the game when their respective actions happen.*

| Line                                        | Filename                | Description                                                                        | Example                 |
|---------------------------------------------|-------------------------|------------------------------------------------------------------------------------|-------------------------|
| **Move or Die!**                            | `menu@game_title`       | The name of the game in the main menu, this should sound epic (but not omitted to) | <video src="" controls> |
| **Select your character**                   | `menu@select_character` | When player joins the lobby and character selection begins                         | <video src="" controls> |
| **Select your favorite modes**              | `menu@vote_start`       | When game modes voting begins                                                      | <video src="" controls> |
| **Let's do this**                           | `menu@vote_end`         | Plays right before the match starts                                                | <video src="" controls> |
| **Time to pick a mutator**                  | `game@mutator`          | Plays when players get to select a "mutator"                                       | <video src="" controls> |
| **5, 4, 3, 2, 1**                           | `game@countdown`        | Countdown (appears at the end of round and somewhere else in future)               | <video src="" controls> |
| **Ready? GO!**                              | `game@go`               | Plays when round starts                                                            | <video src="" controls> |
| **Draw**                                    | `game@draw`             | When players are in equal situation and nobody wins                                | <video src="" controls> |
| **Time's up**                               | `game@time_up`          | When the time runs out and nobody wins                                             | <video src="" controls> |
| **Sudden death! No more life regeneration** | `game@sudden_death`     | Plays in the pre-end of round                                                      | <video src="" controls> |
| **Nobody wins**                             | `menu@nobody_win`       | Plays at end round when nobody won in this round                                   | <video src="" controls> |
| **Blue wins**                               | `menu@blue_win`         | Announces that Blue player won in the round                                        | <video src="" controls> |
| **Yellow wins**                             | `menu@yellow_win`       | Announces that Yellow player won in the round                                      | <video src="" controls> |
| **Pink wins**                               | `menu@pink_win`         | Announces that Pink player won in the round                                        | <video src="" controls> |
| **Green wins**                              | `menu@green_win`        | Announces that Green player won in the round                                       | <video src="" controls> |
