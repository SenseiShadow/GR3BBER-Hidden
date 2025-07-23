# GR3BB4R HIDDEN

This is a terminal application that verifies a key and monitors for MTA process to launch an executable.

## Files Created:
- `terminal.exe` - Main terminal application
- `key.txt` - Contains the verification key "SenseiShadow"
- `data/game.exe` - Executable that will be launched when MTA is detected

## How it works:
1. The terminal displays "Verifying Key..." 
2. It reads the key from `key.txt` and checks if it matches "SenseiShadow"
3. If valid, it displays "Valid Key"
4. Then it shows "Waiting game..." and monitors for MTA process
5. When MTA is detected, it waits 2 seconds and launches `data/game.exe`

## Usage:
```bash
# Run the terminal.exe

# put your executable in data
data/game.exe | it has to be called that
```

## Requirements:
- Python 3
- psutil library (installed via apt: python3-psutil)

## Note:
The system monitors for any process containing "mta" in its name. Make sure to have MTA (Multi Theft Auto) or a similar process running to trigger the executable launch.




# Proyecto Protegido

Este proyecto está protegido bajo la licencia **CC BY-NC-ND 4.0**.  
🔒 **No se permite uso comercial ni modificaciones.**

**Autor original:** [github.com/SenseiShadow](https://github.com/SenseiShadow)
