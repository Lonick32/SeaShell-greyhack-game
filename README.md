<h1 style="font-size: 28px;">SeaShell 1.0.7 WIP</h1>
<h1> A collection of scripts written for use in the game grey hack https://store.steampowered.com/app/605230/Grey_Hack/ </h1>
<br>
<small> WIP </small><br>
<small> **Nightly** --> most commits reading "kind" can be used in the public build </small><br>

<b> Acknowledgments </b><br>
// Thank you @github: WyattSL for the GreyHack Game documentation<br>
// Thank you @github: psimonson for https://github.com/psimonson/greyhack-scripts/tree/master/v0.8/scripts<br>
// Thank you to the members of the GreyHack community & discord<br>
<br>
## INSTALL ##
# FILESYSTEM #<br>
1.) Use installer to create the required file structure, (*be sure to launch as home user*) alternatively you can: <br>
*create a folder named src, and place all scripts inside of it via the game code editor <br>
 <br>
-- You can pass the src code from here to the files, then easily compile them all using the installer <br>
-- adjust the paths for the refernce code in main.src and payload.src <br>
ex: import_code("/home/USER/src/utils.src") -- only if done manually !!
# COMPILE #<br>
-- You will need to compile the following files in this order, name the binary the same as the src<br><br>
<br> MAIN PROGRAM <br><br>
~~1.) objects.src --> ** MUST ALLOW IMPORTS **<br>~~
2.) core.src --> ** MUST ALLOW IMPORTS **<br>
3.) utils.src --> ** MUST ALLOW IMPORTS **<br>
~~4.) modules.src --> ** MUST ALLOW IMPORTS **<br>~~
5.) main.src --> RENAME TO ss <br>
<br> ESCALATION <br><br>
~~1.) cargo.src --> name to cargo <br>~~
Once complete, the only required filed are ss, ~~and cargo<br>~~
# LOCAL DB # (NPC PW hashes)<br>
1.) Youll need the dictionary files from https://github.com/linuxgruven/dictionary<br>
2.) The script will ask you to paste the contents into the script, using CTRL+SHIFT+V copy the correspnding.src to the terminal running installer.<br>
3.) You will be prompted for your user in order for the builder script to build the hashes <br>
4. The installer script can be ran in stages, or provides a full installation. 

DELETE ALL SRC FILES ONCE YOU HAVE SUCCESFULLY RAN SS<br>
<h1>SeaShell Features </h1><br>
1.) Manage multiple objects in a sandbox environment<br>
2.) Capture net sessions remotely, return exploit objects from launched binaries<br>
3.) Internal & External LAN bouncing <br>
4.) Extensive surf mode which intends to replicate all vanilla commands<br>
5.) Extended rshell-interface and commands<br>
6.) FileSystem browser, editor, deleter ;)<br>
7.) Service Manager & Site Builder<br>
& More !<br>
<br>This tool easily handles negative karma 0-2 missions, and while not inteded directly for PvP, is a valid option
<br>
<h2> Usage</h2><br>
I have had some questions on how to best utilize in game & Here are some tips; <br>

1.) When capturing and utilizing shell objects, For *Most* commands in surf_mode you must mount; then launch the binaries to run commands on your newly captured machine<br>
2.) Most commands work passed to a computer object, obviously things a shell can do, a computer cannot itself. <br>
3.) If you are getting errors when it comes to file paths, please first check your permissions, there are some places i might forget<br>
4.) Exploit menu is somewhere between deprecated and redundant, ill let you decide<br>
<br>
Hope you enjoy if you find useful;<br>
![image](https://github.com/Tuna-Terps/SeaShell-greyhack-game/assets/62733984/20922457-d403-4512-9a2d-465dd22f844f)"<br>
"Surf Mode"<br>
<img src="https://github.com/Tuna-Terps/SeaShell-greyhack-game/assets/62733984/8ace3ea9-e893-4500-8403-532803dd9d98" alt="Surf Mode" width="750" height="1000">
<br>
port entry<br>
<img src="https://github.com/Tuna-Terps/SeaShell-greyhack-game/assets/62733984/5497579a-73ce-410a-8fce-650ba427b51b" alt="Port Entry" width="750" height="750">
<br>
exploit menu<br>
<img src="https://github.com/Tuna-Terps/SeaShell-greyhack-game/assets/62733984/aab42764-d65a-4d3d-9c51-b23d483b7096" alt="Exploit Menu" width="500" height="350">
<br>
<img src="https://github.com/Tuna-Terps/SeaShell-greyhack-game/assets/62733984/fc0ae38b-00b1-4e5e-a98b-429c71787bf0" alt="Exploit Menu" width="500" height="350">
<br>
<img src="https://github.com/Tuna-Terps/SeaShell-greyhack-game/assets/62733984/63499508-1dc8-4c17-bee8-bfefd4b6e184" alt="Exploit Menu" width="500" height="350">
<br>
global objects<br>
<img src="https://github.com/Tuna-Terps/grey-hack-game-scripts/assets/62733984/244a98e5-bd64-4911-9383-a8cd5578e942" alt="Global Objects" width="500" height="350">
<br>
LAN mappin<br> 
<img src="https://github.com/Tuna-Terps/SeaShell-greyhack-game/assets/62733984/482ef634-330e-412c-bbf8-0d58eae222e0" alt="LAN Mapping" width="750" height="1000">
