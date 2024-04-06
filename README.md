Xray Core with http upgrade and ws


## Compilation

### Windows (PowerShell)

```powershell
$env:CGO_ENABLED=0
go build -o xray.exe -trimpath -ldflags "-s -w -buildid=" ./main
```

### Linux / macOS

```bash
CGO_ENABLED=0 go build -o xray -trimpath -ldflags "-s -w -buildid=" ./main
```

