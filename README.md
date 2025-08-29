# GoldSplits (Alpha)

GoldSplits is a tool for timing speedrun attempts with automatic checkpoints and real-time comparisons against your personal best run.

Please report issues or provide suggestions on the [nexus discord](https://discord.gg/raidcore) and include screenshots, recordings or logs where applicable. This is an early alpha release so expect that there will be bugs and future releases may break compatibility with your personal bests.


## Usage
There is no configuration required to start a run, just indicate that you are ready and the timer will automatically start once you move. Checkpoints are triggered automatically by reading the event status from the game memory. Everytime an instance is completed, the run will be saved to a file in the addon directory. You can stop the timer after each instance or time multiple consecutive instances and times will always be compared against your personal best for that instance. Personal bests will be recalculated and saved once the timer is stopped.


## Known problems
- Only raids are supported at this time. Support for other types of instanced content will be added after the alpha.
- The interface may not look correct if your imgui styles do not perfectly match my own.


## Disclaimer
Source code for this addon will remain closed because it accesses memory to read game data and call functions from the Guild Wars 2 client.
