+Codename: RMSusano'o
+Engine: RPGMaker XP
+Author: PedroHLC
+Version: 0.7.3 - BETA
+Publish Date: 05/12/2011
+Last Update Date: 10/09/2011

+Thanks for:
  * HugoLnx
  * Anderson Porto
  * DarkD.Vicious
  * 灼眼的夏娜

+What's New?
  + 0.0.0
    * Netplays are now compatible (almost).
    * You don't need to be an Administrator.
    * RTP doesn’t have to be included.
  + 0.0.3
    * Protect password added.
  + 0.0.5
    * Optimized Code (Speed UP)
  + 0.2.0
    * vgvgf RGSSAD Extractor blocked (temporary)
  + 0.5.0
    * RGSS103J.DLL Blinded
  + 0.5.1
    * 60% more fast
    * Online Switch
    * RGSS102e.DLL Blinded
  + 0.5.2
    * Removed some temporary codes
  + 0.5.3
    * Optimized Code (Speed UP)
  + 0.6.0
    * Less Ruby More C++ (:-D)
  + 0.6.1
    * Now Game.exe needs to be named Game.exe
  + 0.6.2
    * Version of RGSS changed to 102E
    * It doesn't need to configure if the game is on/off anymore.
    * Fixed the bug that causes the game stop in Windows Vista/Seven
  + 0.6.3
    * Graphics and Audio can be encrypted too
    * Other protections were added
  + 0.7.0
    * Encypter converted to C++
    * Added a debug file (BETA)
    * Impossible to open to players at the same time
  + 0.7.1
    * RGSS.DLL place changed to %TEMP%
    * Some bugs resolved
    * WinSock fixed
  + 0.7.2
    * BUg do SE corrigido
  + 0.7.3
    * where is key.cfg?
    * Now the encryption password had to have 9 letters
  
+To encrypt your project use the following:
0) Make a backup of your project
1) Extract the program in your project folder
2) #ONLY FOLLOW THIS STEP IF YOUR GAME IS ONLINE:
    Substitute the script "Winsock" (that comes w/ your netplay) for the one in the file "winsock.txt"
3) Add the script of the file "script4graphics.txt" in the game scripts
4) Run the file "encrypter.exe", when this line apper 'Digite uma senha[...]' type an encryption password/key
5) Move the folder "Backup" to a safe folder out of your project
6) Delete these files: "compilador.exe", "debug.txt", "script4graphics.txt", "winsock.txt", "readme.txt", "msvcr100d.dll" and "leia-me.txt"
7) Delete any RGSS Libraries ("RGSS10XX.dll") that are in the project folder (if your project need, you don't need to delete the "RGSS102E.dll")
8) #only follow this step if your game ISN'T online: Delete the file "WSR.dll"