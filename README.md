# Windows-Spooler-Fix

This batch script fixes your always "offline" printer in the sh1t printer spooler of windows 10 and 11 (should also work for windows 7 and 8) 

# INSTRUCTIONS
1. Download the script
2. Open it with the notepad or other raw text editors
3. In line 2 change < PRINTER NAME > with your printer name (can be separated by a space), delete < and >
4. Do the same for line 3
5. Save the batch file
6. Launch it as an administrator (right click => run as administrator)

# FAQ
1. The program says: cannot find registry key. SOLUTION: Check your printer name in the file, you might as well like to check regedit (win+r then type regedit) printer name, located at "HKEY_CURRENT_CONFIG\System\CurrentControlSet\Control\Print\Printers\"
2. The program says: access denied. SOLUTION: Run the script as an administrator, right click then run as administrator
