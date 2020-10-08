# sandstormmapcycle
Map Cycle generator for custom servers for Insurgency Sandstorm

# Usage
powershell -file "./genmap.ps1" -mode -lighting -side

powershell -file "./genmap.ps1" -mode "Checkpoint,Outpost" -lighting Day -side Security

powershell -file "./genmap.ps1" "Checkpoint,Outpost" Day Security

powershell -file "./genmap.ps1" "Checkpoint,Outpost"

powershell -file "./genmap.ps1" Domination

powershell -file "./genmap.ps1" Domination Day

powershell -file "./genmap.ps1" Checkpoint

Please note, quote multiple gamemodes and seperate with commas.

# Exporting Results
To export to a file simply use standard operators: > to replace contents of file >> to append to contents of file.
powershell -file "./Genmap.ps1" Domination Day > C:\Temp\Mapcycle.txt
