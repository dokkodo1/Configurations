

All of this only needs to be done once. Grab a cup of coffee, spend the 15 or so minutes it takes to go through this slowly and meticulously, and all will be well!
Oh and remember... REAPER is not free! The devs are very generous in giving the community a fully-fledged indefinite trial for this incredible software. A personal use license is only 60USD and the commercial license is 225USD.
This is an absolute steal when compared to any other production software these days. 
Here's is a link to purchase your license!

http://reaper.fm/purchase.php



——DOWNLOADS——


Download REAPER:
https://www.reaper.fm/download.php

Install REAPER to default location and open it up and let it load, then close it.
There’s a splash screen and a pop-up telling you that “REAPER is not free” etc. Just wait the 5 seconds and click “still evaluating”.

Download SWS Extensions (x64):
https://www.sws-extension.org
(ARM64 is only for Apple M1 or M2)

Download ReaPack (x86 / 64-bit):
https://reapack.com


——INSTALLS——

MAC:


Install SWS and ReaPack:
- Open REAPER
- Click “Still evaluating” after the splash screen finishes its countdown
- Options > Show REAPER resource path in explorer/finder (important folder)
- If you don’t have a .../UserPlugins/ folder, create one in the …/REAPER/ directory
- Close REAPER
- Install SWS from the executable you downloaded previously. You don't need to read anything, just install to default location.
- Copy or drag “reaper_reapack-x86_64.dylib” file into …/REAPER/UserPlugins/

Download ReaPack libraries:
- Open REAPER
- Extensions > ReaPack > Manage Repositories (this menu might have opened when you started the program, in which case you can still follow these steps) > Options > Install new packages when synchronising
- Apply
- Wait for downloads to complete, it may take a while.
- just click "OK" on everything and restart the program again...
- if the language selector appears, choose english and "Load always".


Windows:


Install SWS and ReaPack:
- Open REAPER
- Click “Still evaluating” after the splash screen finishes its countdown
- Options > Show REAPER resource path in explorer/finder (important folder)
- If you don’t have a ...REAPER/UserPlugins/ folder, create one in the …/REAPER/ directory
- Close REAPER
- Install SWS from the executable you downloaded previously. You don't need to read anything, just install to default location.
- Copy or drag “reaper_reapack-x64.dll” file into …/REAPER/UserPlugins/

Download ReaPack libraries:
- Open REAPER
- If there's a "Manage Repositories" window that pops up, just follow the steps anyway.
- Extensions > ReaPack > Manage Repositories > Options > Install new packages when synchronising
- Apply
- Wait for downloads to complete, it may take a while.
- just click "OK" on everything and restart the program again...
- if the language selector appears, choose english and "Load always".



—CONFIGURATIONS—


Import Config:
- REAPER ("Options" on Windows) > Preferences… > General > Import configuration… (default shortcut for preferences is cmd+, [comma] or ctrl+p)
- Import the “HPL REAPER Config Full.ReaperConfigZip” file (Don’t unzip)
- Apply

When REAPER restarts you may have to configure the launcher, if not then skip this step:
"Whoops! Couldn't load Lokasenna's GUI library v2 for Lua...
- Hit "Okay" to close to pop-up
- in the top bar, Actions > Show action list (shortcut for actions list is "?" or "shift + /")
- in the text field, "filter" type "set loka gui"
- click on the script that comes up and hit enter or press "run" at the bottom of the actions list

- To disable the launcher go to Extensions > Startup Actions > Clear global startup action

Select your audio interface:
- REAPER ("Options" on Windows) > Preferences > Audio > Device > Audio Device

Select default path to save new projects:
- REAPER > Preferences > General > Paths
- Leave everything blank except the first path. Save to documents or dropbox or wherever, mine looks like this
  "Dokkodo’s dropbox directory/[PROJECTS]/REAPER MEDIA"

Set default project path:
- REAPER ("Options" on Windows) > Preferences > Project
- Clear any text from the text field at the top. If you’d like REAPER to open up to a particular project template them this is where you select the template. If left blank, a blank project will open upon start.

Configure MIDI Devices:
- REAPER ("Options" on Windows) > Preferences > Midi Devices:
My config will come with a bunch of MIDI devices I’ve used. Feel free to highlight everything and remove them all and start from fresh.
There is no major drawback to not doing so. This menu allows you to set various parameters for MIDI control through connected devices. You can choose if REAPER will receive MIDI input, CC, and clock, as well as set the individual devices ID.

Set up Plug-in paths:
- REAPER ("Options" on Windows) > Preferences > VST
Check that the text fields are pointing towards your plugin folder where all the .dll files are.
Multiple paths are separated by semicolon ie
“C/Program Files/VST 3/;E/My Plugins/“
^ no spaces between different paths
- Do the same for LV2/CLAP though I doubt you have LV2 or CLAP plugs.

DARK MODE!!!!! (Only available if your MacOS default is set to dark mode):
- REAPER > Preferences > General > Advanced UI/system tweaks… > Allow 10.14+ dark mode if enabled

Project Defaults:
- File > Project Settings… > Media
- The first text field, if there’s nothing there, type in “Media Files” or “Audio Files” or whatever you’d like all your project media to save to, otherwise all project media will go to the folder you’ve created for the project.
- Them click “Save as default project settings”.
- This is also the menu where you can set your project video frame rate, resolution, and audio sample rate
- Also the menu you go to when you want to change how media items behave when you change tempo.

:)

——UPDATES——

I’ll keep this updated with updated keybindings and actions. There is a separate config file which only imports keybindings, mouse modifiers, and actions that you only need to update at will. If you import that keybindings and actions config file, you won’t need to repeat any of the other steps in the future.

——ISSUES——

Keybinds on Windows are still WIP. There is no equivalent to the cmd modifier so if anybody has any suggestions, feel free to message me.
