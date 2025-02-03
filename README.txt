INSTALLATION INSTRUCTIONS:

the directory structure in the CWApp directory is important.  Some important notes
- the "CWApp" directory is the source code for the game.  If you aren't a developer you don't need it.  NOTE:  this directory may not be on GitHub yet.  
- in the "DOWNLOADS" directory are the ZIP files that you'll need to download.

0.  SRC.ZIP - NOT NEEDED FOR THE GAME.  PURELY FOR DEVS WHO WANT TO SEE THE SOURCE CODE.  if present this is the current source code for the game.  This likely won't compile because i've likely not included all the side files it needs, but you can definitely look through the .cls files to see how i coded the game.

1.  MAIN.ZIP - this is the ZIP with the main structure needed to run the app.  Unzip this directory.
- in the App dir (CWApp dir), you should see a CWApp.txt file.  This is the actual EXE.  Youll need to rename it to "CWApp.exe" in order to play.   Make sure you actually change the file extension, and its not still a text file name "CWApp.exe.txt".

- important sub-directories are the "FS\Images" directory and the "FS\Scenarios\CombinedGame\SavedGames" directory, which i'll mention later.


2.  IMAGE_xxx.ZIP - these are the many large images needed by the game. Unzip these and drop the actual .JPG/.PNG file in the "FS/Images" directory in the App folder


3.  Click the .EXE file,  the game should take a few seconds and popup

APPLICATION INFORMATION:
----------------------------------------------------------------

A combination of all the VG Fleet Series game into a single .NET app

Overall Features:
- 3rd Fleet sequence of play
- Combined Orders of Battle from all 5 games
- Hundreds of expansion ships/units that were researched for the 1990-1991 timeframe of the game

Main Differences from physical game:
- Enemy units are not shown on map unless they are detected
- Action Sequence is done differently.  Each side gives orders to all active units.  Automation executes moves and attacks.  Still adheres to combat and detection rules.
- Strategic Movement.  Units can either start off-map or travel off-map between the formal map areas from the game.  Global coverage.
- Game will not allow units of both sides to start game in same hex, but during automation, game will allow it.  Ships all move one hex at a time so you should be able to avoid that if you like, but the game doesnt care.

Known Features not implemented
- None

Planned Features in progress:
- None
