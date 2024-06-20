## Install Balatro Steammodded 1.0.0 alpha on winlator
A guide to run Balatro on winlator with steammodded 1.0.0 alpha.

This simple method is to use Windows emulator (in this case winlator) to effortlessly install lovely and steammodded 1.0.0 alpha.

### Preparation
- [Balatro](https://store.steampowered.com/app/2379780/Balatro/?l=tchinese) (the game itself)
- [Latest winlator build](https://github.com/brunodev85/winlator/releases)
- [Latest Lovely build](https://github.com/ethangreen-dev/lovely-injector/releases)
- [Steammodded 1.0.0 alpha build](https://github.com/Steamopollys/Steamodded/archive/refs/heads/main.zip)

### Installation
1. Install winlator and run the app
2. In the settings menu, set both box86 and box64 preset to `Stability`
3. Create new container
4. Click more (three dots) > run
5. Put Game directory (normally it will be `C:\Program Files(x86)\Steam\Steamapps\common\Balatro`) directly into `C:\` (It will look like `C:\Balatro`)
6. __Install lovely:__ Put `version.dll` into `Balatro` folder
7. Start menu > System Tools > Wine Configuration
8. In the `Libraries` tab, type `version` into the textbox > click `Add` > OK
9. __Install Steammodded:__ Put `Steammodded` folder in `C:\users\xuser\AppData\Roaming\Balatro\Mods`
10. Run the game (Balatro.exe) and run enough rounds to go through tutorial seed
11. Then put mods of your choise into the same directory as step 9
12. Enjoy

### References
- [Balatro Game Page](https://www.playbalatro.com/)
- [Winlator GitHub](https://github.com/brunodev85/winlator)
- [Lovely GitHub](https://github.com/ethangreen-dev/lovely-injector)
- [Steammodded GitHub](https://github.com/Steamopollys/Steamodded)
