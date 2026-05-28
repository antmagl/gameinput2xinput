VERY IMPORTANT!!! MUST READ
Everything that isn't from andrew-ld, it's made purely with AI. It's not a lot of code in reality, probably a hundred of lines, but this fixed vibration on KCD2, using this dll.

readme is work in progress

# gameinput2xinput
This library partially reimplements gameinput using xinput.

# Installation with wine
- Copy gameinput2xinput.dll to the same directory as the game's main executable, then rename it to gameinput.dll.
- add the following launch option to the game's properties: `WINEDLLOVERRIDES="gameinput=n,b" %command%`

# Tested games
- Kingdom Come: Deliverance II (FIXED VIBRATION ON LINUX)
