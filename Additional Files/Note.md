# Bellow code is needed to save in "notepad $profile" command to work the theme properly every time the prompt opens.


clear
oh-my-posh init pwsh --config 'C:\Users\Tanvir\AppData\Local\Programs\oh-my-posh\themes\Tanvir1.omp.json' | Invoke-Expression

set-PSReadLineOption -PredictionViewStyle ListView
