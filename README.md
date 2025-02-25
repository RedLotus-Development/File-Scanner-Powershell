# File-Scanner-Powershell
RedLotus-FileContentScanner
- A Powershell Script to scan file contents for predefined strings.
![image](https://github.com/user-attachments/assets/df0d168b-f3ec-47bd-aba3-ad1464ef9cd2)

Banner Format:
 Write-Host -ForegroundColor DarkRed "  ____          _ _          _             "
 Write-Host -ForegroundColor DarkRed "|  _ \ ___  __| | |    ___ | |_ _   _ ___ "
 Write-Host -ForegroundColor DarkRed "| |_) / _ \/ _` | |   / _ \| __| | | / __|"
 Write-Host -ForegroundColor White "|  _ <  __/ (_| | |__| (_) | |_| |_| \__ \"
 Write-Host -ForegroundColor White "|_| \_\___|\__,_|_____\___/ \__|\__,_|___/"
 Write-Host
 Write-Host -ForegroundColor Red "By UnMonsieur - Red Lotus"

# **How to Edit**
1) $extensions - specify a * and extension (i.e "*.exe" for executables")
2) $strings - ASCII strings to scan matching extensions files for (i.e "requireAdministrator" for executables that require Administrator to be run)
3) $path - path to parse recurvisely, including its sub-directories (i.e "C:\Users\" to scan files in C:\Users\ and its sub-dirs)
4) Results are saved in the directory command is being run from.
