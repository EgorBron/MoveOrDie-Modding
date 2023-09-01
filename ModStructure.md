# Move or Die mod structure

Any mod in Move or Die must follow the one structure of files and folders.

There you can learn how it defines and works.

## Basic mod

Let's begin from a scratch to create our fresh empty mod.

Any mod can be located in:
* `Mods` folder in the game directory
* in the Steam's Workshop directory (by default `<Steam directory>/steamapps/workshop/content/323850/<workshop ID>/`
* directly in `Lib` or `Src` or `Levels` or any other

For local development it is recommended to use **only the `Mods` folder**.

There are several files already in here:
```
./Example Mod (change this name)/
Mods go here.txt
steam_autocloud.vdf (optional)
```

> "Example mod" folder is a empty mod too, but we'll create own manually. If you're *too lazy*, you can just copy that folder and tweak metadata.
>
> Inside the "Mods go here.txt" we can find a small notice from developers about the official modding manual. Btw, mostly obsolete and useless.
>
> And the "steam_autocloud.vdf" is Steam's autosync file, nothing special, but don't touch this!

To create your mod, you need to make a folder with a name (which should probably refer to the actual name of the mod). *If you think that it should be done through `Mod Manager`, you're wrong.*

In such folder, you also need to create some files:
* `steamthumbnail.png` with resolution 512x512 - the mod icon in Steam workshop
* `thumbnail.png` with resolution 180x80 - the mod banner in the game
* `modinfo.txt` with contents like below - the mod metadata
* ```json
  {
  	"name":"Change to actual name of your mod",
  	"author":"Paste your Steam username here",
  	"description":"Write short description of the mod here.",
  	"category":"Replace to one of theese: Character, Level, Game Mode, Audio, UI, Environment, Item, Misc"
  }
  ```

And that's it - you're created the empty mod that does nothing!

Note that the main mods feature is **replacement of original game files**. That's means, you can use your mod to create/replace **any** content in the entrie Move or Die, but you **must** follow original folders structure.

> If you want to create own announcer - at the top level of mod you need to create `Lib/Sound/Announcer/<your announcer name>/` and add required announcer files.
> 
> If you want to replace default Bomb Tag level to your own creation - at the top level of mod you need to create `Levels/BombTag-Square.level` which is a MoD Level Editor file.

Now, navigate to certain guide of content you want to mod!
