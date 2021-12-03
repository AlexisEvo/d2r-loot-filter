# A mediocre purely mod-based D2:R loot filter

This is a mod for D2R that makes it easier to quickly discern which items you would want to pick up, essentially implementing a pseudo loot filter. 

PRs welcome. Open an issue or join us on [Discord](https://discord.gg/aajDbCNc9x) for feedback.

![img1](https://i.imgur.com/cydb7qL.jpg)

![img1](https://i.imgur.com/BJJzwX3.jpeg)

# Disclaimer

Although this strictly uses the game's built in modding support, we do not know Blizzard's stance on using mods on battle.net. The nature of D2 modding means that only visual mods can be used online, which is what this mod is. If Blizzard were opposed to it I believe they'd disable modding support online entirely. If I receive a response or contact from a Blizzard employee, I will happily take down all copies of the mod. 

# Installation

1. Download the repo as a zip using the Code button at the top of the page
2. Create a directory in your D2 installation folder named "mods", copy the lootfilter directory into this folder. 
3. If done correctly, the directory layout should match https://i.imgur.com/hZAvJI6.png
4. Edit game settings in your battle.net launcher and add "-mod lootfilter -txt" to your parameters, https://i.imgur.com/LG9Fpn2.png
5. Launch the game and enjoy a more pleasant D2R experience 🥰

# Development

If you want to make changes to the mod, you may want a full installation of it rather than just the files changed.

1. Download CascView from http://www.zezula.net/en/casc/main.html
2. In CascView open storage and select your D2R folder
3. Once opened navigate to data/data. You should see three folders named global, hd, and local. Extract these folders into the D2R/Data folder. This will require around 30 GB of disk space. Keep in mind, cascview won't extract these folders like u expect -- it might nest them into data/data/data/. Extract them into a separate folder and copy over the 3 dirs you need. If done correctly your data folder will now look like https://i.imgur.com/HCRtp9G.png (at least one cutie needed to move cascview to her d2r folder to work -- ymmv)
4. Extract the loot filter files into your Data folder. When Windows prompts you, select overwrite all. If Windows does not prompt you to overwrite files, you fucked something up.
5. Edit your game shortcut to add -direct -txt to the end. If using battle.net launcher, you can set this in game properties. https://i.imgur.com/kgP3VFZ.png

# FAQ

* It didn't install right -- not a question, but you did something wrong, refer to screenshots
* Can X/Y/Z be done? -- probably not, if you're looking for item rarity it isn't possible
* Does this slow down act switching? -- yes, if you use the -direct -txt method. Get a faster SSD or use the MPQ.
* How can I make edits? -- view the commit history on top of the page and read how I'm making changes.
* How do I edit MPQs? -- http://www.zezula.net/en/mpq/download.html
* My game crashes often, is it the loot filter? -- I run 5x clients, 1x loot filter 4x vanilla. All crash equally. Blame Blizzard.

# Donations

If you want to pay me back, consider donating to one of the following charities

* [HRC](https://give.hrc.org/page/62714/donate/1?locale=en-US)
* [Internet Archive](https://archive.org/donate/)
* [EFF](https://supporters.eff.org/donate/join-4)
* [ACLU](https://action.aclu.org/give/now)

I ain't above accepting d2 pixels lmao send fg to @Lexibug on jsp if you can't spare a couple bucks to humanity.
