# GoldSplits (Alpha)

GoldSplits is a tool for timing speedrun attempts with automatic checkpoints and real-time comparisons against your personal best run.

## Usage
There is no configuration required to start a run, just indicate that you are ready and the timer will automatically start once you move. Checkpoints are triggered automatically by reading the event status from the game memory. Everytime an instance is completed, the run will be saved to a file in the addon directory. You can stop the timer after each instance or time multiple consecutive instances and times will always be compared against your personal best for that instance. Personal bests will be recalculated and saved once the timer is stopped.

## Disclaimer
This is an early alpha release, there will be bugs and stuff that doesn't work.

Please report issues on the [nexus discord](https://discord.gg/raidcore) and include screenshots, recordings or logs where applicable.

## Known problems
- GoldSplits is currently unable to tell the difference between an event hiding or an event that is completed. Where possible the addon will try to correct itself if you wipe and retry a boss but be careful with stopping the timer after a wipe on the final boss because this may override your personal best. Fixing this requires checkpoints to be re-worked but further research is needed first.
- Checkpoints will not trigger if you game client language is not set to English. This will also be fixed by the checkpoint rework.
- Only raids are supported at this time. Support for other types of instanced content will be added after the alpha.
- The interface may not look correct if your imgui styles do not perfectly match my own. 
