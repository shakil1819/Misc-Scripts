File: README.TXT for Windows 10 Debloater Tool (Version 2.2) from www.FreeTimeTech.com
Based on 2 PowerShell Scripts (1) Chris Titus Tech GitHub PowerShell Scripts (2020-21): https://github.com/ChrisTitusTech/win10script
and (2) farag2 Sophia Script for Windows GitHub PowerShell Scripts (2021): https://github.com/farag2/Sophia-Script-for-Windows

►Link: https://freetimetech.com/windows-10-clean-up-debloat-tool-by-ftt/
►YouTube: https://www.youtube.com/watch?v=3KTRS1RpBmg

Check our Windows 11 Debloater from www.FreeTimeTech.com website: 
►Link: https://freetimetech.com/windows-11-debloater-tool-debloat-gui/

Check our other version of Windows 10/11 Debloater called 'Sophia Script for Windows' on BenchTweakGaming.com website: 
►Link: https://benchtweakgaming.com/2020/10/27/windows-10-debloat-tool/
This other version is made in collaboration with farag2 (Dmitry Nefedov).

Update v2.2
-----------
Added ToolTip languages: NL, EL, AR and TR.

Update v2.1
-----------
Added ToolTip languages: DE, IT, and RO. Folder called 'Localizations' created to store all tooltips.txt files.

Update v2.0
-----------
The tabs to create a customized PowerShell script and run has changed to use Sophia Script functions. Old radiobutton 
saved presets not compatible with this new version. UI has been updated. There is a 'Windows Default' preset. Bug fixes.
There are many ToolTip languages for radiobuttons: EN, RU, PL, FR, ES, PT, CN, KR, JP and VN. More to come!

INTRODUCTION
------------
Please read this document to understand how to use this program.

There is a 'EZ Debloater' tab page as main front of the program. It allows you to run common
PowerShell scripts to debloat Windows 10. There are several restore/undo scripts you can choose from 
after if you choose. Some buttons in the 'EZ Debloater' tab page has ToolTips (message popups) for 
more information.

Each button has a script you can see to modify if you want before running.

The other tabs allows you to create a PowerShell script file that you can run to finely tweak/'Debloat' 
Windows 10.

The options are arranged in different tabs and there is a preset 'Debloat Preset' in the Options menu. 
You can choose a preset first and add your own choices. There is a 'Windows Default Preset' to revert
back to Windows Default setttings. You can also create your own radiobutton presets and share. There 
is also a 'Opposite' menu choice to select the alternate radiobutton choices. This is good to revert 
the changes in a script to run.

In 'Normal' Mode, the 'Read/Edit' radiobutton is missing to clean up the interface. Switch to 'Edit' 
Mode to gain back the 'Read/Edit' button beside each radiobutton to see the PowerShell script.

You can directly run the PowerShell script from the program after creating your script.
Click the 'Run Powershell' button after you fill in the radiobutton choices and click the 
'Output PowerShell' button. The "Run PowerShell" button creates a PowerShell script called
'runpsscript.ps1' in the same directory and runs it.

OR save the PowerShell script as whatever you wish in the same directory with the other files then 
run it using the following commands.

But first, launch PowerShell (Run as administrator) and navigate to where your script is.

1. Set-ExecutionPolicy Unrestricted 
2. ./YOUR_SCRIPT_NAME.ps1

YOUR_SCRIPT_NAME is the name of the PowerShell script you just saved.

FILES
-----
There needs to be 8 files for this program to run properly.

►Windows10Debloater.exe : The GUI program.
►ezdebloater.txt : contains the PowerShell scripts for the 'EZDebloater' tab page.
►data.txt : 	contains the options(function names) to select from (usually only 2 
		options that something is Enable or Disable). Notice the sections 
		and how a comma and double quotes separate them. The last option in 
		each section does not have a comma. Add or substract from the set.
►functions.txt : contains the complete functions named from data.txt. These are the 
		commands that get run. Add or substract from the set.
►debloatpreset.txt : contains debloat preset. Click this option from the menu in program.
►defaultpreset.txt : contains default preset. Click this option from the menu in program.
►tooltips.txt :	Contains ToolTips for each radiobutton option. Many languages so far.

►ooshutup10.cfg : O&O ShutUp10 config for silent install.

►README.txt : This text file for information and link resources.