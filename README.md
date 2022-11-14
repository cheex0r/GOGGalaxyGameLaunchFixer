# GogGalaxyGameLaunchFixer
 Prevents GOG Galaxy when minimizng games when launching.

This program is to fix an issue where GOG Galaxy will minimize a game after it is launched. This tends to happen when using other launchers like Playnite to launch games via GOG Galaxy.

It works by launching a seperate exe which in turns launches the desired game. GOG Galaxy then launches this program, and doesn't minimize the actual game.

Cloud syncing still works with this fix.

To apply the fix:

1. Copy `GOGGalaxyGameLaunchFixer.exe` to the directory of the exe for the game you want to fix.
2. Rename the exe of the game you want to fix to end in `_game.exe`. 
3. Rename `GOGGalaxyGameLaunchFixer.exe` to the original exe name.

Using Cyberpunk 2077 as an example

1. Copy `GOGGalaxyGameLaunchFixer.exe` to `..\Cyberpunk 2077\bin\x64\`
2. Rename `Cyberpunk2077.exe` to `Cyberpunk2077_game.exe`
3. Rename `GOGGalaxyGameLaunchFixer.exe` to `Cyberpunk2077.exe`
