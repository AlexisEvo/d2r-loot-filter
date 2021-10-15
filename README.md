# A mediocre purely mod-based D2:R loot filter

This probably will not get you banned as it strictly uses the game's modding support, without relying on injection or hooks. That said, Blizzard has banned for MPQ edits in the past -- breakpoint hacking, farcast, etc. Use at your own risk.

PRs welcome. Open an issue or join us on [Discord](https://discord.gg/aajDbCNc9x) for feedback.

![img1](https://i.imgur.com/cydb7qL.jpg)

![img1](https://i.imgur.com/BJJzwX3.jpeg)

# Installation

1. Download CascView from http://www.zezula.net/en/casc/main.html
2. In CascView open storage and select your D2R folder
3. Once opened navigate to data/data. You should see three folders named global, hd, and local. Extract these folders into the D2R/Data folder. This will require around 30 GB of disk space. Keep in mind, cascview won't extract these folders like u expect -- it might nest them into data/data/data/. Extract them into a separate folder and copy over the 3 dirs you need. If done correctly your data folder will now look like https://i.imgur.com/HCRtp9G.png (at least one cutie needed to move cascview to her d2r folder to work -- ymmv)
4. Extract the loot filter files into your Data folder. When Windows prompts you, select overwrite all. If Windows does not prompt you to overwrite files, you fucked something up.
5. Edit your game shortcut to add -direct -txt to the end. If using battle.net launcher, you can set this in game properties. https://i.imgur.com/kgP3VFZ.png
6. Enjoy and hope Blizzard doesn't ban us 🥺

someone has shown me the way i pwomise this will get easier to install

# FAQ

* It didn't install right -- not a question, but you did something wrong, refer to screenshots or use the MPQ from Discord (MPQs will eventually be available under Releases)
* Can X/Y/Z be done? -- probably not, if you're looking for item rarity it isn't possible
* Does this slow down act switching? -- yes, if you use the -direct -txt method. Get a faster SSD or use the MPQ from Discord.
* How can I make edits? -- view the commit history on top of the page and read how I'm making changes.
* How do I edit MPQs? -- http://www.zezula.net/en/mpq/download.html
* My game crashes often, is it the loot filter? -- I run 5x clients, 1x loot filter 4x vanilla. All crash equally. Blame Blizzard.


# Donations

I kindly appreciate the warm thoughts! I am living relatively comfortable. If you want to pay me back, consider donating to the [HRC](https://give.hrc.org/page/62714/donate/1?locale=en-US), the [Internet Archive](https://archive.org/donate/), the [EFF](https://supporters.eff.org/donate/join-4), or the [ACLU](https://action.aclu.org/give/now). These are all foundations I value far more than my own efforts. If you do, please send me a receipt -- knowing one of these foundations has a couple extra bucks makes anything I do worthwhile.

I ain't above accepting d2 pixels lmao send fg to @Lexibug on jsp if you can't spare a couple bucks to humanity. 