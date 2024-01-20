## Oh my posh installation

https://www.hanselman.com/blog/my-ultimate-powershell-prompt-with-oh-my-posh-and-the-windows-terminal  
https://docs.microsoft.com/pl-pl/windows/terminal/tutorials/custom-prompt-setup  
https://github.com/dahlbyk/posh-git#overview  
https://github.com/devblackops/Terminal-Icons  

Install Windows terminal without Store: use Add-AppxPackage (name of the package)

```powershell
## powershell $PROFILE:
Import-Module posh-git  
Import-Module oh-my-posh  
Import-Module -Name Terminal-Icons  
Import-Module PSReadLine  
Set-PoshPrompt -Theme ohmyposhv3  
```