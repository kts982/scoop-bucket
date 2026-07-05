# scoop-bucket

Scoop bucket for [kts982](https://github.com/kts982) tools.

## Usage

```powershell
scoop bucket add kts982 https://github.com/kts982/scoop-bucket
```

## Packages

| Package | What | Source |
|---|---|---|
| `sap-odata` | SAP OData explorer — CLI (`sap-odata.exe`) | [sap-odata-explorer](https://github.com/kts982/sap-odata-explorer) |
| `sap-odata-explorer` | SAP OData explorer — desktop app (portable) | [sap-odata-explorer](https://github.com/kts982/sap-odata-explorer) |

```powershell
scoop install sap-odata            # CLI
scoop install sap-odata-explorer   # Desktop app
```

Binaries are unsigned; SHA256 hashes in each manifest are pinned against the
GitHub release's `SHA256SUMS.txt`, and each release page carries per-asset
VirusTotal links.
