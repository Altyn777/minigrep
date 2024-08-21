### Commands

```bash
cargo run -- frog poem.txt
IGNORE_CASE=1 cargo run -- to poem.txt
cargo run -- to poem.txt true
cargo run -- to poem.txt > output.txt
```

```PowerShell
PS> $Env:IGNORE_CASE=1; cargo run -- to poem.txt
PS> Remove-Item Env:IGNORE_CASE
```
