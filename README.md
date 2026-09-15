# Nbtstat

CSC VB6 NetBIOS/MAC helper (project Project1). Loads host,IP CSV lines, shells `NBTSTAT -a` via `c:\temp\nbt.bat` into `c:\temp\nbtinfo.txt`, parses `MAC Address =` lines into host,MAC,IP lists, cleans spaces from IPs, and Exports the results.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`Nbtstat.vbp`) | VB6 | WinForms exe | NBTSTAT MAC Address collector/exporter |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Nbtstat.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Windows `nbtstat` command available on PATH / system

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Nbtstat`.
Company names in project files: CSC.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
