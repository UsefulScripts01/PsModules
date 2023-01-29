## PsModules

### VMModule

#### Innstalation

Copy the code from the area below and paste it into PowerShell Admin (or Windows Terminal).

```powershell
Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope Process -Force
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/UsefulScripts01/PsModules/main/VMModule.psm1" -OutFile "C:\Windows\Temp\VMModule.psm1"
Import-Module -Name "C:\Windows\Temp\VMModule.psm1" -Scope Global
```
