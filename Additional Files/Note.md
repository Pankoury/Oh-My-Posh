# Bellow code is needed to save in "notepad $profile" command to work the theme properly every time the prompt opens.
# Check username by typing "whoami" in cmd.


clear
oh-my-posh init pwsh --config 'C:\Users\***(user)\AppData\Local\Programs\oh-my-posh\themes\Tanvir1.omp.json' | Invoke-Expression

set-PSReadLineOption -PredictionViewStyle ListView
