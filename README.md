# CS-GO-config
CS:GO config madeby me
	This README in simple explain what are the active keys
	CS:GO autoexec.cfg by BarVaz -  Last Update: 30/08/2020 .
	Download from Github: https://github.com/BarVazz/CS-GO-config
	This config is not meant to be used "out of the box", but to look up commands, ConVars and binds and to help you create your own personalized config.
	If you look for an easier way to create your own config or want to copy pro players settings, check out this Map by crashz' and MisterIO:
	https://steamcommunity.com/workshop/filedetails/?id=1325659427

	I recommend that you use a text editor like "Notepad++" or "Sublime" to edit this file.
	https://notepad-plus-plus.org/
	https://www.sublimetext.com/
	
	HOW TO INTALL:
	Put the File "autoexec.cfg" into the following folder if you want the same autoexec to be used across multiple accounts on the same system:
	...\SteamApps\common\Counter-Strike Global Offensive\csgo\cfg
	¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
	Put the File "autoexec.cfg" into the following folder if you want separate autoexec's for each account (i.e. If you share your PC with your family/friends):
	...\Steam\userdata\<YOURID>\730\local\cfg
	¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
	You will see a message in the console if the autoexec gets loaded on game start and you will also hear a sound when you execute the config manually.
	If the config does NOT load automatically, then simply add "+exec autoexec" to your Launch Options.
	Here is how you do this:
	Rightclick on CS:GO in your steam library and select Properties -> Set Launch Options... -> Then add: "+exec autoexec" (without the "")
	If you have other Launch Options, keep them separated with a space. It will look like this: " -console -novid -high +exec autoexec.cfg -tickrate 128" (without the "")
	More info: https://steamcommunity.com/sharedfiles/filedetails/?id=379782151
	To get a list of all available commands and console variables, type "cvarlist" (without the "") into console and press [ENTER].
	To get additional information about a specific command or console variable, use "help <command>" or "help <cvar>" (without the "").
	PRO TIP: Use the command "differences" (without the "") to get a list of all convars which are not at their default values.
	BarVaz's Config by `.BarVaz.` Last Updated: 30/08/2020
	Version 3.5

	------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------//

	Content
	1. Mouse and Sensitivity
	2. Crosshair Customization
		2.1 More Crosshair Customization
			2.1.1 `.BarVaz.`  old crosshair
			2.1.2 7Ducks crosshair
			2.1.3 Sm1ley crosshair
			2.1.4 crosshair S1mple
	3. Binds, Scripts and toggles
		3.1 Keyboard
		3.2 Mouse
		3.3 NumPad
		3.4 ArrowKeys
		3.5 ControlPad up from ArrowKeys
		3.7 FKeys
	4. Network and Interpolation Settings
	5. Net graph
		5.1 Shows on scoreboard only
		5.2 Shows always
	6. Radar / HUD settings
	7. Viewmodel \ Weaponhand position
	8. Aliases - DO NOT EDIT BELOW THIS LINE (unless you know what you do)!
		8.1 AutoBuy Weapon
		8.2 Switch hands
		8.3 Jump+Duck
		8.4 Plant the bomb with a message
		8.5 Show the Scoreboard  and netgraph
		8.6 Toggle ingame Voice (ON/OFF)
		8.7 Toggle custom Crosshaircolors (//bind z _chColor)
		8.9 Admin binds
		8.10 Reset your score
		8.11 mutet and unmutet (on/off)
		8.11 Mutet and unmutet (on/off)
		8.12 Mutect and unmutect (on/off)
		8.13 Muteall and sm_unmuteall (on/off)
		8.14 Edit spawns
		8.15 Show damage after dying |Toggleconsole & clear | Sound Effect
		8.16 Chat spam
	9. Others
	10. Up The Achievements
	11. Sound Settings
	12. SPECTATOR SETTINGS
	12.1 Freezecam and death/killer panel
	12.2 Spectator replay (Gamemode Casual MM).
	12.3 Spectator X-Ray
	13. EXPERIMENTAL

	------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------//
	
	1. Mouse and Sensitivity
	#####################
	
	This part handles mouse settings without active keys 
	
	------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------//

	2. Crosshair Customization
	#######################
	
	This part handles Crosshair settings without active keys
	You can choose which Crosshair you want by turning the Crosshair on and off with "//"
	See this picture for basic crosshair adjustments: http://steamcommunity.com/sharedfiles/filedetails/?id=799950821
	Also keep in mind that the same settings for size, thickness and gap look different on other resolutions. That means:  

	------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------//
	
	3. Binds, Scripts and toggles
	##########################
	
	To get a list of all aliases, type `alias` into console and press [ENTER].
	If you want to know to what command/alias a key is bound, type `bind KEY` into your console.
	To list all keys bound to a command/alias, type `key_findbinding COMMAND` or `key_findbinding ALIAS` into console.
	If you want a list of all keybinds, type `key_listboundkeys` into console (you can use `unbindalljoystick` first to remove all joystick/controller binds).
	The names for right CTRL, right SHIFT and the ALT GR keys are "Rctrl", "Rshift" and "Ralt" (upper or lowercase doesn't matter).
	Important: "Ralt" also counts as keypress for "CTRL" (the left one) so use the command `hideoverviewmap` with it to close the overview map!
	The names for the Windows keys are "Lwin" and "Rwin" and the names for the Numpad keys can be found under the buy binds section in this config.

	3.1 Keyboard
	##########################
	
	0				-	Slot for weapon
	1				-	Slot for weapon
	2				-	Slot for weapon
	3				-	Slot for weapon
	4				-	Slot for weapon
	5				-	Slot for weapon
	6				-	Slot for weapon
	7				-	Slot for weapon
	8				-	Slot for weapon
	9				-	Slot for weapon
	A				-	Move left
	B				-	Open the buy menu to buy weapons and equipment
	C				-	Open the radio menu 3
	D				-	Move right
	E				-	Pick up weapons / plant bomb / take a hostage
	F				-	Look on your own weapon
	G				-	Drop current Weapon
	H				-	(No active key)
	I				-	Toggle ignoring of radio Messages ("Fire In The Hole" and similar) on and off	
	J				-	Toggle ignoring of BROADCAST messages (press x1) / TEAM+BROADCAST messages (press x2) / ALL messages (press x3)
	K				-	(No active key)
	L				-	Toggle enemy team mute ON/OFF
	M				-	Team selection (press 1 for T and 2 for CT)
	N				-	(No active key)
	O				-	Toggle ingame Voice (ON/OFF)
	P				-	(No active key)
	Q				-	Switches to last used weapon. Also used for spectator/demo watching function to show the "Graphs"
	R				-	Reload weapon
	S				-	Move back
	T				-	Open menu to apply spray on surface you are currently aiming at
	U				-	Team Chat
	V				-	Plant the Bomb and send massage to your team
	W				-	Move forward
	X				-	Open the radio menu 
	Y				-	All Chat 
	Z				-	Open the radio menu 1
	`				-	Toggle Console on the Key above Tabulator/left of "1" (bind `toggleconsole` to toggle or use `openconsole` and `closeconsole`)
	TAB				-	Show the Scoreboard  and netgraph
	ESC				-	Cancel select
	CAPSLOCK		-	(No active key)
	SHIFT			-	Walk (slow) and clean all the bullet holes and blood splatters in the map
	CTRL			-	Duck/Crouch and clean all the bullet holes and blood splatters in the map
	R-ALT			-	Open the vote menu (hideoverviewmap is to close the map that opens because rALT also counts as CTRL)
	R-WIN			-	Send massage to your team "I pressed the Windows key! Tabbing back into the game..."
	L-WIN			-	Send massage to your team "I pressed the Windows key! Tabbing back into the game..."
	SPACE			-	Jump
	-				-	(No active key)
	=				-	(No active key)
	[				-	(No active key)
	]				-	Loop say inall chat	
	;				-	(No active key)
	'				-	(No active key)
	\				-	(No active key)
	,				-	(No active key)
	.				-	(No active key)
	/				-	(No active key)
	
	
	3.2 Mouse
	##########################
	
	MOUSE1			-	*PewPewPew* Also has the same function as `spec_next` when spectating
	MOUSE2			-	Change firemode or zoom or remove/attach silencer. Also has the same function as `spec_prev` when spectating
	MOUSE3			-	(No active key)
	MOUSE4			-	Team radio.
	MOUSE5			-	(No active key)
	MWHEELUP		-	Scroll-Up to jomp
	MWHEELDOWN"		-	Scroll-Down to jomp
	
	
	3.3 NumPad
	##########################
	
	Numpad 0		-	Say to all: "Good Luck, Have Fun"
	Numpad 1		-	Say to all: ":D:D LOL"
	Numpad 2		-	(No active key)
	Numpad 3		-	(No active key)
	Numpad 4		-	(No active key)
	Numpad 5		-	(No active key)
	Numpad 6		-	(No active key)
	Numpad 7		-	Autobuy: M4 / AK, primammo, secammo ,vest+helmet, vest, grenade, smoke, flash, decoy, incindiery, molotov, defuser
	Numpad 8		-	Rebuy (buy again your lest buy)
	Numpad 9		-	Autobuy: primammo and secammo
	Numpad DEL		-	Say to all: "GLHF"
	Numpad ENTER	-	AutoBuy vest + helmet
	Numpad PLUS		-	AutoBuy AWP
	Numpad MUNUS	-	AutoBuy AWP
	Numpad MULTIPLY	-	AutoBuy MP7
	Numpad SLASH	-	AutoBuy M4 / AK
	
	
	3.4 ArrowKeys
	##########################
	
	UP-ARROW		-	Reset your score in RETAKE servers
	DOWN-ARROW		-	(No active key)
	RIGHT-ARROW		-	(No active key)
	LEFT-ARROW		-	(No active key)
	

	3.5 ControlPad up from ArrowKeys
	##########################
	
	INS				-	AutoBuy grenade
	HOME			-	AutoBuy flash
	PGUP			-	AutoBuy smoke
	DEL				-	AutoBuy decoy
	END				-	AutoBuy molotov
	PGDN			-	AutoBuy defuse


	3.7 FKeys
	##########################
	
	F1				-	Change hand
	F2				-	Toggle show damage after dying
	F3				-	(No active key)
	F4				-	(No active key)
	F5				-	(No active key)
	F6				-	(No active key)
	F7				-	(No active key)
	F8				-	(No active key)
	F9				-	(No active key)
	F10				-	(No active key)
	F11				-	Say "BarVaz's Config V3.5 By `.BarVaz.` "
	F12				-	Do not use this bind, default screenshot!!

	List of weapon slots (usage: "buy [string] [NUMBER]").
	Pistols:					SMGs:				Rifles:					Heavy:					Grenades:					Items:
	2 = Glock/P2000/USP-S		8 = MAC-10/MP9		14 = Galil/FAMAS		20 = Nova				26 = Molotov/Incendiary		34 = Zeus x27/Taser
	3 = Dual Berettas			9 = MP7/MP5SD		15 = AK-47/M4A4/M4A1-S	21 = XM1014				27 = Decoy					
	4 = P250					10 = UMP-45			16 = SSG 08				22 = Sawed Off/MAG-7	28 = Flashbang				# Items that can't be bought via slot number (usage "buy itemname"):	
	5 = Tec-9/FiveSeven/CZ75	11 = P90			17 = SG553/AUG			23 = M249				29 = High Explosive			# defuser	= Defuse Kit (CT only)
	6 = Desert Eagle			11 = P90			18 = AWP				24 = Negev				30 = Smoke					# vest		= Ballistic Vest
	7 *empty*					13 *empty*			19 = G3SG1/SCAR 20		25 *empty*				31 *empty*					# vesthelm	= Ballistic Vest and helmet			


	Traditional buy aliases (usage "buy itemname"): 
	Pistols:	glock, hkp2000, usp_silencer, elite, p250, tec9, fn57, deagle (no alias for CZ-75, use "tec9" or "fn57" instead).
	Rifles:		galilar, famas, ak47, m4a1, m4a1_silencer, aug, sg556 (no alias for M4A4, use "M4A1", "m4a1_silencer" or "AK47" instead).
	Sniper:		ssg08, awp, scar20, g3sg1
	Heavy:		nova, xm1014, mag7, m249, negev (no alias for Sawed-Off, use "mag7" instead).
	SMGs:		mac10, mp9, mp7, ump45, p90, bizon (no alias for MP5SD, use "mp7" instead).
	Armor:		est, vesthelm, heavyarmor
	Utility:	taser, defuser, molotov, incgrenade, decoy, flashbang, hegrenade, smokegrenade, tagrenade

	------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------//

	4. Network and Interpolation Settings
	##########################
	This part handles Network and Interpolation Settings without active keys

	------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------//

	5. Net graph
	##########################
	This part handles Net graph Settings without active keys

	5.1 Shows on scoreboard only
	##########################
	This part handles Net graph (Shows on scoreboard only) Settings without active keys


	5.2 Shows always
	##########################
	This part handles Net graph (Shows always) Settings without active keys

	------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------//

	6. Radar / HUD settings
	##########################
	This part handles Radar / HUD settings without active keys

	------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------//

	7. Viewmodel \ Weaponhand position
	##########################
	This part handles Viewmodel \ Weaponhand position settings without active keys
	
	------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------//

	8. Aliases - DO NOT EDIT BELOW THIS LINE (unless you know what you do)! 
	#######################
	This part handles Aliases settings without active keys
	
	Shortcuts for commands
	@t				-	T team.
	@ct				-	CT team.
	@all			–	All players.
	@alive			-	All alive players.
	@dead			-	All dead players.
	@me				-	Only me.
	@!me			-	Everyone except me.
	@aim			-	Who I'm aiming at.

	8.1 AutoBuy Weapon
	#######################
	This part handles AutoBuy Weapon settings without active keys

	8.2 Switch hands
	#######################
	This part handles Switch hands settings without active keys

	8.3 Jump+Duck
	#######################
	This part handles Jump+Duck settings without active keys
	
	8.4 Plant the bomb with a message
	#######################
	This part handles Plant the bomb with a message settings without active keys

	8.5 Show the Scoreboard  and netgraph
	#######################
	This part handles Show the Scoreboard  and netgraph settings without active keys

	8.6 Toggle ingame Voice (ON/OFF)
	#######################
	This part handles Toggle ingame Voice (ON/OFF) settings without active keys

	8.7 Toggle custom Crosshaircolors (//bind z _chColor)
	#######################
	This part handles Toggle custom Crosshaircolors (//bind z _chColor) settings without active keys
	
	8.9 Admin binds
	#######################
	This part handles Admin binds settings without active keys

	8.10 Reset your score
	#######################
	This part handles Reset your score settings without active keys


	8.11 Mutet and unmutet (on/off)
	#######################
	This part handles Mutet and unmutet (on/off) settings without active keys

	8.12 Mutect and unmutect (on/off)
	#######################
	This part handles Mutet and unmutct (on/off) settings without active keys

	8.13 Muteall and sm_unmuteall (on/off)
	#######################
	This part handles Muteall and sm_unmuteall (on/off) settings without active keys

	8.14 Edit spawns
	#######################
	This part handles Edit spawns settings without active keys

	8.15 Show damage after dying | Toggleconsole & clear | Sound Effect
	Display Damage with Switch Script!
	#######################
	This part handles Show damage after dying settings without active keys
	
	8.16 Chat spam
	#######################
	This part handles Chat spam settings without active keys

	8.17 Get a list with more sounds here: https://www.reddit.com/r/CounterStrikeBinds/comments/72xc2w/add_a_little_auditory_flourish_to_your_config/
	#######################
	This part handles list with more sounds settings without active keys
	
	------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------//

	9. Misc. Settings
	#######################
	This part handles Misc. settings without active keys

	------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------//

	10. Up The Achievements
	####################### 
	This part handles Up The Achievements without active keys

	------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------//

	11. Sound Settings
	##############
	This part handles Sound Settings without active keys
	
	If you experience problems with the sound, try these steps to fix them:
	Disable additional 3D sound processing in your sound card driver or disable Advanced 3D Audio Processing in CSGO.
	Set `snd_mix_async` from 1 (default) to 0.
	Set `snd_mixahead` to 0.025 (default) or slightly higher.

	11.1 To finetune your sound settings, use `sv_cheats 1; snd_debug_panlaw 1` in a local Bot Match.
	##############
	This part handles To finetune your sound Settings without active keys
	
	11.1.1 Headset/Headphone settings:
	##############
	This part handles Headset/Headphone Settings without active keys

	11.1.2 Stereo Speaker settings:
	##############
	This part handles Stereo Speaker Settings without active keys

	11.1.3 Surround Speaker settings:
	##############
	This part handles Surround Speaker Settings without active keys
	
	------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------//

	12. SPECTATOR SETTINGS
	##################
	This part handles SPECTATOR SETTINGS without active keys

	12.1 Freezecam and death/killer panel
	##################	
	This part handles Freezecam and death/killer panel SETTINGS without active keys

	12.2 Spectator replay (Gamemode Casual MM).
	##################
	This part handles Spectator replay (Gamemode Casual MM) SETTINGS without active keys
	
	12.3 Spectator X-Ray
	##################
	This part handles Spectator X-Ray SETTINGS without active keys

	------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------//
		
	13. EXPERIMENTAL
	##################
	This part handle EXPERIMENTAL SETTINGS without active keys

	------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------//


BarVaz's Config V3.5 By `.BarVaz.`
You love it?  send mea message
STEAM:	https://steamcommunity.com/profiles/76561198812968069/
Github: https://github.com/BarVazz/CS-GO-config"
