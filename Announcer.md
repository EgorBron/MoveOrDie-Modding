# Create your own announcer

## Prerequisites
* Any audio editor - e. g. Audacity
* Announcer sound source - either your beautiful voice or memes cut etc
* Text editor (Notepad is enough)
* Move or Die copy

## Notes
* All files **must** be in OGG Vorbis format. There are no file extensions for the part below, but keep in mind that these must still be `.ogg' files.
* You **can do multiple different (or not) phrases per line** - just add a number to the end of file name (e. g. `game@draw.ogg`, `game@draw_2.ogg`). They will play randomly in game.
* Pay attention to the **"mistery" lines**. If you don't know how to announce the line, skip it, and random "mistery" line will play instead (that's also applicable to new or custom game modes). But also do not abuse skipping lines! This can lead, although amusing, to unnecessary situations (since "mistery" lines are very general).

## Example lines

### General

> *Lines for specific situations. These play throughout the game when their respective actions happen.*

| Phrase                                      | Filename                | Description                                                                        | Example                 |
|---------------------------------------------|-------------------------|------------------------------------------------------------------------------------|-------------------------|
| **Move or Die!**                            | `menu@game_title`       | The name of the game in the main menu, this should sound epic (but not omitted to) | <audio src="" controls> |
| **Select your character**                   | `menu@select_character` | When player joins the lobby and character selection begins                         | <audio src="" controls> |
| **Select your favorite modes**              | `menu@vote_start`       | When game modes voting begins                                                      | <audio src="" controls> |
| **Let's do this**                           | `menu@vote_end`         | Plays right before the match starts                                                | <audio src="" controls> |
| **Time to pick a mutator**                  | `game@mutator`          | Plays when players get to select a "mutator"                                       | <audio src="" controls> |
| **5, 4, 3, 2, 1**                           | `game@countdown`        | Countdown (appears at the end of round and somewhere else in future)               | <audio src="" controls> |
| **Ready? GO!**                              | `game@go`               | Plays when round starts                                                            | <audio src="" controls> |
| **Draw**                                    | `game@draw`             | When players are in equal situation and nobody wins                                | <audio src="" controls> |
| **Time's up**                               | `game@time_up`          | When the time runs out and nobody wins                                             | <audio src="" controls> |
| **Sudden death! No more life regeneration** | `game@sudden_death`     | Plays in the pre-end of round                                                      | <audio src="" controls> |
| **Nobody wins**                             | `menu@nobody_win`       | Plays at end round when nobody won in this round                                   | <audio src="" controls> |
| **Blue wins**                               | `menu@blue_win`         | Announces that Blue player won in the round                                        | <audio src="" controls> |
| **Yellow wins**                             | `menu@yellow_win`       | Announces that Yellow player won in the round                                      | <audio src="" controls> |
| **Pink wins**                               | `menu@pink_win`         | Announces that Pink player won in the round                                        | <audio src="" controls> |
