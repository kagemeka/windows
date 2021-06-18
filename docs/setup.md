# Windows Setup 



# [install git](https://git-scm.com/download/win)

# install vscode 


# [install python](https://www.python.org/downloads/windows/)

## set alias 
```powershell
Set-Alias -Name "python3" -Value "C:/Users/<user>/AppData/Local/Programs/Python/Python39/python.exe"

# Set-Alias -Name "python3" -Value <python path>
```

## [install pip](https://pip.pypa.io/en/stable/installing/)

```powershell
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py

python3 get-pip.py

```

## set pip alias 

```powershell 
Set-Alias -Name "pip" -Value "python3 -m pip"
```