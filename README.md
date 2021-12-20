# Metasploit
Metasploit is a framework that enables pentration testing.  There are 4 aspects.  
  
recon
exploit
payload
loot
  
The idea is to bring together modules and data that can help you find vulnerabilities that can be exploited - and then exploit them.
  
the payload is something you will try to send to an exploited system - something you can then run to do whatever task

## Commands
`use` - this allows us to USE a module. 
e.g. `use exploit/windows/browser/adobe_flash_avm2`
  
the module is now loaded - you can see because “msf >” changes to “msf exploit_name >”
  
`show` - this then shows us information about the module
`show info` - gives us information about the module
`show payloads` - shows a list of paylods we can load and try to use (with the current exploit!)
`show targets` - show targets we can attack.
  
`search \[keywords\]` - used to find exploits/payloads etc.  keywords include ‘platform’ (eg windows).  Format:
`search type:exploit platform:windows flash` - this searches for a Flash exploit that works on windows
  
`options` - this shows us the options we can use with the module
  
`set \[option\] \[value\]` - sets options for the module we’re using (like key value pair)
`set SRVHOST 192.168.1.94`
`set SRVPORT 80`
  
`exploit` - begin!

#CLI #metasploit #exploitation #hacking #pentesting
