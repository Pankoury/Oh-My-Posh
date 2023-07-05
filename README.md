# Setting Themes
	1. Download and install 'Terminal' app from store/ update windows to 11 so that get the latest version of 'Terminal' app.
	2. Downloaded 'Dracula' and other themes from here [https://windowsterminalthemes.dev/]
	3. In Terminal Click "Open JSON File" (Bottom Left) and Search for "schemes"
	4. Paste the downloaded theme code at the end using (,).
	5. Then set the theme from settings.

# Installing Oh-My-Posh
	1. Install 'FiraCode' Font from this site [https://github.com/ryanoasis/nerd-fonts/releases/tag/v3.0.2]
	2. Check 'winget' is installed or not by typing "winget" in the terminal.
if not showing "winget", download and install "app installer" from windows store.
	
	3. Follow instruction on this site [https://ohmyposh.dev/docs/installation/windows] to get oh-my-posh theme.
	4. OR Type bellow command  using run as administrator.
- winget install JanDeDobbeleer.OhMyPosh -s winget
		
	  5. Download custom files from [https://github.com/Pankoury/Oh-My-Posh/tree/main]
	  6. Copy custom themes from downloaded directory and paste to bellow directory.
'C:\Users\\***(user)\AppData\Local\Programs\oh-my-posh\themes'

	7. Installing PSReadLine, [to get instruction go to [https://github.com/PowerShell/PSReadLine]
	8. Or type bellow commands step by step.
- Install-Module -Name PowerShellGet -Force
- Install-Module PSReadLine

	  If already installed module type
- Uninstall-Module PSReadLine  [to uninstall previous version first.]
- Install-Module PSReadLine -Force
- Import-Module PSReadLine

      9. Type bellow command in cmd.

- notepad $profile
  
	    10. If shows error, then 1st type bellow command and then again above code. (for help go to [https://ohmyposh.dev/docs/installation/prompt])
- New-Item -Path $PROFILE -Type File -Force

      11. Copy notepad file content (from downloaded folder) and paste it to "notepad $profile".
      12. Install "Meslo" fonts from downloaded folder ( if not installed yet) and set it in tab "Defaults > Appearance> Fonts face>"MesloLGM Nerd font"

That’s all. Thank u.
