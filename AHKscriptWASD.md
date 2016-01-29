# Introduction #

This Wiki is for the script "Diablo III WASD.ahk".

This script provides traditional WASD Movement for Diablo III!

8-way directional movement in both fullscreen and windowed modes that
does not interrupt other actions (such as typing) outside the game!


# Details #

Installation Instructions:

1) Run script with autohotkey (or as standalone .exe after compiling)

2) Start Diablo III

3) If you change window sizes/resolutions or the script fails to initialize properly because Diablo III is already running, right click autohotkey and "Reload This Script" or exit and re-open the standalone .exe (if running a compiled .exe version)

4) Rebind "W" "A" "S" and "D" ingame

5) NOTE Rebind the "move" command in-game to the "F12" key

# Changelog #

v1.2

- Made some changes to mouse distance that should improve the smoothness of the move action

- Reverted to an older polling style from v1.0 that should work for more people. If you were having no issues with v1.1 then you should continue to use that as it takes up less processor time running.

v1.1

- Fixed an issue where character would only move in one direction due to   incorrect values retrieved during script initialization

- Script now closes automatically upon Diablo III closing in any way

- Script will now end the Agent.exe process if it is still running when Diablo 3 has closed.

v1.0

- Added script improvements by Soda

- Mouse pointer no longer jumps around