###équivalence###

cp       devient  Copy-Item
rm       devient Remove-Item
cd       devient Set-Location
mkdir    devient New-Item
man      devient Get-Help
history  devient Get-History
alias    devient New-Alias
cat      devient Get-Content


###les lignes de commandes utilisées###
Get-Command -Verb Copy   pour cp     
Get-Command -Verb Remove     pour rm 
Get-Command -Verb Set      pour cd   
Get-Command -Verb New         mkdir
Get-Help Get-Help    man         
Get-Command -Noun History    pour history 
Get-Command -Verb Set  alias        
Get-Command -Verb Get content  cat      
