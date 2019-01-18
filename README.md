# Launcher

Launch games and applications through [RetroArch](http://libretro.com) + [ChaiLove](https://github.com/libretro/libretro-chailove).

![ChaiLove Launcher Screenshot](Resources/Screenshot.jpg)

## Installation

ChaiLove Launcher can be run through [RetroArch](https://retroarch.com/) and [ChaiLove](https://github.com/libretro/libretro-chailove)...

1. Install [RetroArch](https://retroarch.com)

2. Install [ChaiLove](https://github.com/libretro/libretro-chailove)

3. Download the [ChaiLove Launcher](http://github.com/RobLoach/ChaiLove-Launcher)
	```
	git clone https://github.com/RobLoach/ChaiLove-Launcher.git
	cd ChaiLove-Launcher
	```

4. Create a [chailove-launcher.json](chailove-launcher.sample.json) in either the launcher's directory, the system/BIOS folder, or your save directory, with the games you would like to have in the menu. The following is an example *chailove-launcher.json* file:
	```
	{
		"Steam (Windows)": "C:\\Program Files\\Steam\\Steam.exe",
		"Steam (Linux)": "steam"
	}
	```


5. Launch ChaiLove-Launcher's `main.chai` through RetroArch:
	```
	retroarch -L chailove_libretro.so main.chai
	```

## Controls

- Up: Move selection up
- Down: Move selection down
- A: Launch game
- Start: Launch game
- B: Mute background music

## Attribution

- [Rob Loach](https://robloach.net)
- [Bossa-Nova](https://opengameart.org/content/bossa-nova) by [Joth](https://opengameart.org/users/joth)
- [Mac Apps Icon Set](https://www.deviantart.com/rud3boy/art/Mac-Apps-Icon-Set-354798037) by [Rud3Boy](http://rud3boy.deviantart.com)
- [Metropolis Font](https://fontlibrary.org/en/font/metropolis)
