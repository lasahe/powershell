## Install Oh My Posh & Create PowerShell profile file
`winget install JanDeDobbeleer.OhMyPosh`

`echo 'oh-my-posh init pwsh --config "C:\Users\<USER>\AppData\Local\Programs\oh-my-posh\themes\p10k_lean_edit.omp.json" | Invoke-Expression' > $PROFILE`
(Edit username)

Check profile: `notepad $PROFILE`


- Save theme file to the location 
