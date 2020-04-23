# PoE Tweaker

Fine-tuning utility for the game Path of Exile, featuring performance tweaks coming from community efforts in attempt to make this game run smoother. Contains some extra performance boosting features, known from paid utilities heavily advertised on Steam (but completely FREE). Programmed to be as easy to use as possible. Just set and forget!

**Download:** [Latest release](https://github.com/chris-wolcen/PoE-Tweaker/releases/latest)
**VirusTotal:** [Scan](https://www.virustotal.com/gui/file/7a52ba5c337fb35ccd9388637c4f62c11fc87ccd0bb96c5ada0a76ace6469723/detection)

### Preview

![PoE Tweaker](preview.gif)

### Program features

#### Launcher
Handy function allowing to quickly launch the game with different sets of command line parameters.  
Also allows to create a desktop shortcut with selected set of parameters.

#### Drop Rights
Allows to run the game without Administrator privileges (works with desktop shortcut creation too!).  
This method utilizes WinAPI functions to create a process with restricted (Normal User) token.

#### Sounds
Allows to actually DISABLE (not only mute) selected sounds.   
This can reduce CPU load and improve overall performance.

#### Cache
Allows to purge selected Shader Cache folders.   
According to players, purging Shader Cache helps to reduce stuttering.

#### Defrag
Allows to "defrag" game data file, by rebuilding it and removing obsolete entries.   
Can reduce file size up to few gigabytes. Said to improve load times.

#### Power Settings
Allows to throttle CPU state by adjusting Windows Power Management settings.  
Limiting "Maximum processor state" by few percent off, can be helpful in case of "CPU" hogging" issue and prevent CPU overheating.

#### CPU Affinity
Allows to assign less (or more) CPU resources to the game.  
Limiting cores available to the game, can help with freezes related to "CPU hogging" issue.  
These settings are preserved and applied automatically every time the game starts (as long as this program is running).  
Also has a feature to move other processes to unused cores for an extra performance boost.
 
#### Memory Usage
Monitors Path of Exile memory usage. Allows to force the game to release memory if it has consumed too much.   
Helpful in case of memory leaks, especially on low memory systems. Use with caution!

#### Miscellaneous
* Minimize game when sent to background  
  Helps to save CPU/GPU usage when Alt-Tabbed. Only works if this program is running.
* Make production_Config.ini read-only  
  Prevents overwriting game settings by ingame Options menu.
* Instantly disconnect on pressing a hotkey  
  Causes an instant disconnection by dropping all TCP connections of game process. Useful for HC. 

More features coming in next release...

### Download

**Download:** [Latest release](https://github.com/chris-wolcen/PoE-Tweaker/releases/latest)

#### System requirements
Windows 7, 8.1, 10 x86/x64. No depedencies*.  
*\* .NET Framework only required for LibGGPK.dll (defrag functionality) to work, though you should already have it in your Win10*

#### Installation
Extract the archive and run.  

#### License
Freeware
