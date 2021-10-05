# Optional add-ons to the main loot filter

## Double teleport fix

If you have high enough cast rate, or a higher latency connection, you'll notice that holding down teleport will occasionally "stutter" and cast teleport twice before moving. Higher FCR, or higher ping, the more often it happens. This mod changes Teleport to have a 2 frame cooldown which solves the issue in most cases.

NOTE: this causes spells like Blizzard/Meteor/etc to put Teleport on cooldown. If you want this fixed, tell Blizzard to fix the 'localdelay' field in skills.txt

To install, drop this skills.txt into Data/global/excel/ and overwrite the existing skills.txt. Do this every update.