
# Powershall commands every developer should use 
The commands listed below are a good starting point for any developer, but to fully realize the benefits, you should master parameters and other methods as well,i hope enjoy it

some suggest for better use for powershall

main online repository powershall : [powershall Gallery](https://www.powershellgallery.com/)



## How to use powershall

install powershall from git : [powershall repository](https://github.com/PowerShell/PowerShell/releases/tag/v7.3.4)

```
check your version powershall
$PSVersionTable
PSVersion                      7.1.14409.1018 

```
## cheatsheet commands

![learn powershall ](https://iili.io/HWMjae.png)


## filesystem cmdlet

| command | Alies | Description  | 
| :---          |     :---:      |          ---: | 
| move-item     | mv         | move your file |
| Get-item      | gi         | get items |
| remove-item   | rmdir      | remove your directory |
| New-Item      | mkdir,md   |  create new directory|
| write_output  | echo       | displaying lines of text & create | 
| Clear-Content | clc        | The Clear-Content cmdlet deletes  content files | 
| Get-Content   | cat,gc     | displaying lines of text & create | 
| cipher        |            | Displays or alters the encryption of directories and files on NTFS  |


## Os cmdlet

| command | Alies | Description  | 
| :---         |     :---:      |          ---: | 
| Format-Table    | ft       | formatting of the output of your Windows PowerShell commands |
| Get-Process     | gps      | get all process your cpu |
|Get-Package       |         | get all program  |
|Install-Package    |        | install any program |
|Uninstall-Package  |        |  Uninstall any program |
| Start-Process   | start,saps    | open any format file |
| Get-PSDrive     | gdr      | display all disk drive  |
|  Stop-Process   | kill     | stop process cpu | 
| Clear-Host      | cls,clear      | clear terminal command | 
| Get-Service     | gsv   | displaying all services | 

## hardware scan & anlayze
comptible for windows server 

| command          | Alies              | Description
| :---             | :---:              |  :---:
| systeminfo       |                    | displaying all information compotents  | 
| powercfg         |                    | Powercfg is a very powerful command for managing and tracking how your computer uses energy. | 
| chkdsk           |                    | will immediately scan the drives, without a need to restart the computer | 
| schtasks         |                    | will immediately scan the drives, without a need to restart the computer | 
| Format           |                    | Will Full Format disk drive | 
| taskkill         |                    | You can force stop a program using taskkill -im followed by the executable's name | 
| full shutdown    |  shutdown/s        | full sutdown pc | 
| Restart-Compute  |  shutdown/r        | Restart pc | 


## network command

| command          |  Description |
| :---             |   :---:      |
| ping             |  can reach some destination IP address or domain name | 
| pingpath         | analyzes the route taken and computes packet loss on a per-hop basis | 
| ipconfig         | most-used networking command & shows every network adapter on your system  | 
| Getmac           | get mac address on your system  | 
| tracert          | tracks the route of the packet as it hops from server to server | 
| netsh            | tool for network statistics, diagnostics | 
| arp              | displays the current ARP on your network  | 
| nslookup         | For regular folks like you and me, its main use is finding out the IP address behind a certain domain name | 


## Permission command

`CACLS files /e /p {USERNAME}:{PERMISSION}`

| command 		    |  Description			         |
| :---    		    |   :---:     			         |
| R			          | read-only access 		       | 
| W			          | write-only access 		     | 
| C			          | change (write)  		       | 
| F			          | full access (Full control) | 
| N			          | no access 			           | 
| M			          | modify access 		         | 
| RX			        | read and execute access  	 | 
| D			          | delete access 		         | 
