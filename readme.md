
# command line intrface cheatsheet 
download lastest powershall version :["https://github.com/PowerShell/PowerShell/releases/tag/v7.3.4"]
thanks for @powercode

```
check your version powershall
$PSVersionTable
PSVersion                      7.1.14409.1018 

```

## command for working file & folders

| command | Alies | descripton  | 
| :---         |     :---:      |          ---: | 
| move-item     | mv       | move your file |
| Get-item      | gi       | copy your file |
| remove-item   | rmdir    | remove your directory |
| make-file     | mkdir    | copy your file |
| write_output  | echo     | displaying lines of text & create | 
| Clear-Content | cls,clear      | The Clear-Content cmdlet deletes the contents of an item | 
| Get-Content   | cat,gc     | displaying lines of text & create | 


## Table cheatsheet for os command
| command | Alies | descripton  | 
| :---         |     :---:      |          ---: | 
| Format-Table    | ft       | move your file |
| Get-Process     | gps       | copy your file |
| Start-Process   | start,saps    | remove your directory |
| Get-PSDrive     | gdr    | copy your file |
|  Stop-Process   | kill     | displaying lines of text & create | 
| Clear-Content   | cls,clear      | The Clear-Content cmdlet deletes the contents of an item | 
| full shutdown   | shutdown/s     | displaying lines of text & create | 
| Restart-Compute | shutdown/r      | The Clear-Content cmdlet deletes the contents of an item | 
| Get-Service     | gsv   | displaying lines of text & create | 



## example codes

```
Get-Content -Path Yourfile.log -Tail 30 -Wait 
cat some.doc 

if you define Alias your restart action
sal -Name res -Value shutdown-s
Get-Alias -Name res

```

