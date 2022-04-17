# Sleep
AutoIt Version: V3.3.6.1 [X32] ;~ Windows Version: WIN_XP [X86] ;~ Language: English (0409) #AutoIt3Wrapper_Au3Check_Parameters=-d -w 1 -w 2 -w 3 -w- 4 -w 5 -w 6 -w- 7 local $free,$label,$Drive,$status,$usb ToolTip("Enumerating Drives please wait...", 10, 10, "Loading drives...", 1) Sleep(2000) ToolTip("")  Local $aDrives = DriveGetDrive("REMOVABLE")
