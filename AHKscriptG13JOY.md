# Introduction #

This Wiki page covers the script "Diablo III G13JOY.ahk"

The script provides movement control for Diablo III using the analog joystick on the Logitech G13!

360 degree movement using a G13 joystick that does not interrupt other actions (such as typing) outside the game!


# Details #

Installation Instructions:

1) Dowload the Joystick Test from the AutoHotkey website:  http://www.autohotkey.com/docs/scripts/JoystickTest.htm

2) Run Joystick Test scrip to determine the number for your G13's joystick

3) Change the "JoystickNumber" variable to whatever number corresponds with your G13 joystick

4) Run Diablo III G13JOY script with autohotkey (or as standalone .exe after compiling)

5) Start Diablo III

6) Bind the Move key ingame to "F12"

7) If you change resolutions at any point after running the script, you must close Diablo III and restart the script then reload the game to get the resolution recalculated

# Troublshooting #

- information to be added as it is acquired

# Change-log #

v1.4

- Changed some variables to make operation smoother. If you were having no problems previously then this version isn't necessary, but it should make the script smoother for most people

v1.3

- Fixed an issue where character would only move in one direction due to incorrect values retrieved during script initialization

- Script now closes automatically upon Diablo III closing in any way

- Script will now end the Agent.exe process if it is still running when Diablo 3 has closed.


v1.2

- Added some new configurable variables see source for notes

- Reduced the size of the anchor points resulting in tighter movements

- Changed the way Joystick input was utilized resulting in a smoother        experience


v1.1

- Added script improvements by Soda

- Mouse pointer no longer jumps around the screen


v1.0

- Initial release no changes made