cargo run -- frog poem.txt
IGNORE_CASE=1 cargo run -- to poem.txt

**_PowerShell_**
PS> $Env:IGNORE_CASE=1; cargo run -- to poem.txt
PS> Remove-Item Env:IGNORE_CASE
