# Local-Network-Trojan-NEW-version-
This is a project in which we can access a PC/Laptop's CMD.

I IMPROVE THIS PROJECT FROM: https://github.com/Ashii198/Local_Network_Trojan

I add:
  
- "Attacker's autorun.bat"  
- "Victim's autorun.bat" 
- "script.vbs" (for execute "game.py" in background, and the Victim will not use the game, all is hide from the Victim's screen)


HERE IS IT A SUMMARY:

1. Install Python (for Attacker and Victim)
2. Download this folder (Trojan) and drag in from Downloads to Desktop (for Attacker and Victim)
3. Set the IP as an Attacker on "server.py" and "game.py"

4. The Attacker's needed files:
- Attacker's autorun.bat (on the autorun folder by pressing WINDOWS + R and write "shell:startup", modify the "YOUR USERNAME" place with your username)
- server.py (let it in the desktop folder "Trojan")

5. The Victim's needed files:
- Victim's autorun.bat (let it in the desktop folder "Trojan", modify the "YOUR USERNAME" place with your username)
- game.py (let it in the desktop folder "Trojan")
- script.vbs  (on the autorun folder by pressing WINDOWS + R and write "shell:startup", modify the "YOUR USERNAME" place with your username)


THE PROCESS:

1. The Attacker start the PC (than the "Attacker's autorun" will start the "server.py" automatically)
2. The Victim start the PC (than the "script" will will start the "game.py" without showing anything at the user, every time the PC will be started)
3. Use command "cmdon" to have access and use any command you want
4. Use command "cmdoff"


*** READ ALL THE COMPLETED INSTRUCTIONS ON "INSTRUCTIONS.txt" ***