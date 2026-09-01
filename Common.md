# Common

powershell.exe

Displays Help
Get-Help

Get-Help Get-Process -Full

Download Help file from Internet and saves on file share
Save-Help
Update-Help


Lists all PowerShell command
`Get-Command`

An alias is a shortcut or alternate for a commandlet
Get-Alias

Get-Help
help
Get-ChildItem
gci


Get-Alias -Definition Get-ChildItem

Get and Set Date time of system
Get-Date
Set-Date

Get List of running processes

`Get-Process`
`Get-Process | Select-Object Name,Id`
`Get-Process | Select-Object Name,Id -First 5`
`Get-Process | Select-Object Name,Id -Last 10`

Stop Windows Services
Stop-Service

Restart-Service


Delete file
Remove-Item


Write-Error
Write-Warning
Write-Verbose
Write-Output
Write-Host
Write-Debug
Write-EventLog

Objects and Pipeline

Get-Process | Get-Member
Get-Service | Where-Object { $_.StartType -eq 'Automatic' }

Get-ChildItem c:\Girish | Sort-Object Length -Descending



Invoke-WebRequest
Get-Alias -Definition Invoke-WebRequest

Invoke-Expression takes a string of text and execute it as a command or script allowing dynamic code execution at runtime

