VERY IMPORTANT!!! MUST READ

DISCLAIMER 
I'm not responsible for any damages, bugs or crashes dealt to your devices. Use this dll at your own risk.

Everything that isn't from andrew-ld, it's made purely with AI.

Qwen understood the vibration functioning of the game using this repo https://github.com/Tivian/KCD2_WirelessVibration. AI gathered the right information and put a fix in the dllmain.cpp. 

# gameinput2xinput
This library partially reimplements gameinput using xinput. My fork fixes vibration specifically on KCD2

# Installation with wine
- Copy gameinput.dll to bin/Win64Shared, in the game's directory.
- add the following launch option to the game's properties: e.g. Steam Launch options `WINEDLLOVERRIDES="gameinput=n,b" %command%`

# Tested games
- Kingdom Come: Deliverance II (FIXED VIBRATION ON LINUX)


## Acknowledgments

This patch has been possible thanks to this repo: https://github.com/Tivian/KCD2_WirelessVibration

* Many thanks to @Tivian and obviously @andrew-ld.

