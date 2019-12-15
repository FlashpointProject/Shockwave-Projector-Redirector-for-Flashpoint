Shockwave Projector Redirector 1.2.1
By Anthony Kleine

	The Shockwave Projector Redirector (SPR) allows
	Shockwave Movies to be played via Flashpoint
	Redirector. 
	
	All versions of the Projector use an identical movie
	upgraded to the respective Director version. Requires
	LeechProtectionRemovalHelp Xtra.
	
Command Line Arguments
	--setTheMoviePath [Uncommon]
	
	Purpose
	It changes the *path* where the game believes it is playing.
	
	Usage
	--setTheMoviePath "https://example.com/"
	
	
	
	--setTheMovieName [Uncommon]
	
	Purpose
	It makes the game believe it has a different *filename* than it actually does.
	
	Usage
	--setTheMovieName "metalmayhemworldtour.dcr"
	
	
	
	--setTheEnvironment_shockMachine [Uncommon]
	
	Purpose
	It convinces the game that it is, or is not, playing in *Shockwave.com’s ShockMachine.*
	
	Usage
	--setTheEnvironment_shockMachine 0
	
	Possible Values
	-0
	-1
	
	
	
	--setTheEnvironment_shockMachineVersion [Uncommon]
	
	Purpose
	It sets the version of *Shockwave.com’s ShockMachine* the game believes it is playing on.
	
	Usage
	--setTheEnvironment_shockMachineVersion ""
	
	
	
	--setThePlatform [Uncommon]
	
	Purpose
	It convinces the game it is playing on a *Mac* when it is actually playing on *Windows* or vice-versa.
	
	Usage
	--setThePlatform "Windows,32"
	
	Possible Values
	-"Windows,16"
	-"Windows,32"
	-"Mac,PowerPC"
	
	
	
	--setTheRunMode [Common]
	
	Purpose
	It makes the game believe it is playing in the Director interface, in a Projector or in the browser, regardless of where it is actually playing.
	
	Usage
	--setTheRunMode "Author"
	
	Possible Values
	-"Author"
	-"Projector"
	-"Plugin"
	
	
	
	--setTheEnvironment_productBuildVersion [Uncommon]
	
	Purpose
	It convinces the game it is playing on a different Product Build Version of the software than it actually is.
	
	Usage
	--setTheEnvironment_productBuildVersion "593"
	
	
	
	--setTheProductVersion [Uncommon]
	
	Purpose
	It convinces the game it is playing on a different *Product Version* of the software than it actually is.
	
	Usage
	--setTheProductVersion "11.5"
	
	
	
	--setTheEnvironment_osVersion [Uncommon]
	
	Purpose
	It allows you to set the *OS version* the game believes it is playing on.
	
	Usage
	--setTheEnvironment_osVersion "Windows Vista"
	
	
	
	--setTheMachineType [Uncommon]
	
	Purpose
	It convinces the game it is playing on a *Mac* when it is actually playing on *Windows* or vice-versa *in older games.*
	
	Usage
	--setTheMachineType 256
	
	Possible Values
	-0 to 255 _(Mac)_
	-256 _(Windows)_
	
	
	
	--setExternalParam [Common]
	
	Purpose
	It sets parameters that are being passed from the webpage to the game outside the browser.
	
	Usage
	--setExternalParam "sw1" "http://oneweakness.com" --setExternalParam "SRC" "nwmgmain.dcr"
	
	
	
	--forceTheExitLock [Common]
	
	Purpose
	It forces the *Exit Lock* on or off.
	
	Usage
	--forceTheExitLock 0
	
	Possible Values
	-0
	-1
	
	
	
	--forceTheSafePlayer [Uncommon]
	
	Purpose
	It forces on or off `the safePlayer` property.
	
	Usage
	--forceTheSafePlayer 0
	
	Possible Values
	-0 _(Default)_
	-1
	
	
	
	--disableGoToNetMovie [Common]
	
	Purpose
	It prevents the current movie from going to other, online movies.
	
	Usage
	--disableGoToNetMovie
	
	
	
	--disableGoToNetPage [Common]
	
	Purpose
	It disallows the game from opening any webpage in the browser.
	
	Usage
	--disableGoToNetPage
	
	
	
	--bugfixShockwave3DBadDriverList [Common]
	
	Purpose
	It fixes a crash that occurs with Shockwave 3D games on Nvidia graphics cards.
	
	Usage
	--bugfixShockwave3DBadDriverList
	
	
	
	--do [Common]
	
	Purpose
	It allows you to run Lingo code in the scope of the game being curated after it has been loaded.
	
	Usage
	--do "set the text of member('Example') to 'Hello World'"
	
	
	
	--doBefore [Uncommon]
	
	Purpose
	It allows you to run Lingo code in the scope of the game being curated before it has been loaded.
	
	Usage
	--doBefore "alert('I am a jelly donut!')"
	
	
	
	--go [Common]
	
	Purpose
	It selects a frame to go to in the movie.
	
	Usage
	--go 2
	
	
	
	--preload [Uncommon]
	
	Purpose
	It determines how the game is preloaded.
	
	Usage
	--preload #movie
	
	Possible Values
	-void
	-#netThing
	-#movie
	
	
	
	--noDirectX7 [Uncommon]
	
	Purpose
	It prevents DirectX 7 from being used, which solves issues with Windows 10's software rendering.
	
	Usage
	--noDirectX7
	
	
	
	--newScriptName [Uncommon]
	
	Purpose
	It sets the name of a new script to insert into the game.
	
	Usage
	--newScriptName "My Script"
	
	
	
	--newScriptText [Uncommon]
	
	Purpose
	It sets the text of a new script to insert into the game.
	
	Usage
	--newScriptText "on exitFrame" --newScriptText "go(1)"
	
	
	
	--newScriptType [Uncommon]
	
	Purpose
	It sets the type of a new script to insert into the game.
	
	Usage
	--newScriptType #parent
	
	Possible Values
	-#movie _(Default)_
	-#score
	-#parent
	
	
	
	--trace [Debug Only]
	
	Purpose
	It enables tracing messages to appear in the Message Window.
	
	Usage
	--trace 1
	
	Possible Values
	-0 _(Default)_
	-1
	
	
	
	--traceLoad [Debug Only]
	
	Purpose
	It enables trace loading messages to appear in the Message Window.
	
	Usage
	--traceLoad 1
	
	Possible Values
	-0 _(Default)_
	-1
	-2
	
	
	
	--traceLogFile [Debug Only]
	
	Purpose
	It copies messages that appear in the Message Window to a log file in SPR's folder.
	
	Usage
	--traceLogFile "messages.txt"
	
	
	