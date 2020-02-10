# Unnamed-Stats-Viewer
Public repo for Unnamed Stats Viewer, a World of Warship Matchmaking Monitor with a minimalistic look.
This repo will be used both for Updates and Bug reports.
You can find the latest version [here](https://github.com/yesod30/Unnamed-Stats-Viewer/releases/latest).  
**WARNING**: your antivirus could recognize this as a virus. It's a false positive, since it's missing the Microsoft developer signing.

## Current Features
- Automatically get the statistics for all the player and for the teams in the current match. For cross-server clan battles, only the currently selected region partecipants will be shown. Players with hidden statistics will not be shown.
  - Shown Statistics are Win rate, Battles, Average Damage, Kill/Death Ration and XP.
    - XP is base XP plus premium account modifier, since Wargaming API doesn't give a way to get the true base XP.
  - Team stats are **weighted** averages on the number of battles. This means that the more battles a player has, the more influence it will have over the average. This is to minimize the effects of outliers having a really low number of games.
- Customization of the various color treshold for the different stats.
- Ability to open the wows-numbers page of a player by clicking on his name.
- Automatically detect Updates. Automatic update coming soon (TM).

## Features to be implemented
- Add PR to the stats
- Add ability to use wows-numbers treshold as color treshold.
- Add server selector above teams.

## Bug reports
To report a bug you can either open a new issue [here](https://github.com/yesod30/Unnamed-Stats-Viewer/issues), or write to me on Discord (Yesod30#3558). In both cases, please attach the crash report you can find in the program folder (called DK.Warships.Viewer) inside Roaming. To Access the Roaming folder, open the start menu, type "%appdata%" and press enter.
