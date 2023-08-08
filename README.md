# Installing Terminal & Setting Themes
	1. Download and install 'Terminal' app from store or update to windows-11 so that get the latest version of 'Terminal' app.
	2. Downloaded 'Dracula' and other themes from here [ https://windowsterminalthemes.dev/ ]
	3. In Terminal Click "Open JSON File" (Bottom Left) and Search for "schemes"
	4. Paste the downloaded theme code at the end using (,)
	5. Then set the theme as default from settings.


# Installing Oh-My-Posh
	1. Open "Terminal" as Administrator.
	2. Check 'winget' is installed or not by typing "winget" in the terminal.
		-if not showing "winget", download and install "app installer" from windows store.

	# Another Title:
	3. Follow instruction on this site [ https://ohmyposh.dev/docs/installation/windows ] to get oh-my-posh theme.
	4. OR Type bellow command  using run as administrator.
		- winget install JanDeDobbeleer.OhMyPosh -s winget

	5. Download custom files from [ https://github.com/Pankoury/Oh-My-Posh/tree/main ]
	6. Download custom themes and paste to bellow directory.
		-'C:\Users\\***(user)\AppData\Local\Programs\oh-my-posh\themes'

	7. Installing PSReadLine, [to get instruction go to [https://github.com/PowerShell/PSReadLine]]
	8. Or type bellow commands step by step.
		- Install-Module -Name PowerShellGet -Force
		- Install-Module PSReadLine

	9. If [PSReadLine v 2.0.0 ] already installed then follow bellow instruction-
		- Uninstall-Module PSReadLine  [to uninstall previous version first.]
		- Install-Module PSReadLine -Force
		- Import-Module PSReadLine

	10. Type bellow command in cmd to set notepad profile, sothat every time terminal starts it starts with custom theme.
		- notepad $profile
	11. If shows error, then 1st type bellow command and then again above code. (for help go to [https://ohmyposh.dev/docs/installation/prompt])
		- New-Item -Path $PROFILE -Type File -Force
	12. Copy notepad file content (from github account) and paste it to "notepad $profile".


	13. Install 'FiraCode' and "Meslo" Font from this site [https://github.com/ryanoasis/nerd-fonts/releases/tag/v3.0.2]
    14. and set it in "Defaults > Appearance> Fonts face>"MesloLGM Nerd font"

That’s all. Thank u.
