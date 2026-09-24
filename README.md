# AssetControl

VB6 Asset Control (`Asset Control.exe`) that looks up assets by barcode via ADO (description, type, category, serial) against an Access-style Assets database; includes a V2 tree. Open either `Asset Control.vbp` in the VB6 IDE.

**Source last updated:** 2005-06-01 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `AssetControl` (`Asset Control.vbp`) | VB6 | WinForms exe | Barcode asset lookup via ADO |
| `AssetControl` (`V2/Asset Control.vbp`) | VB6 | WinForms exe | V2 asset control (MDB + browse forms) |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Asset Control.vbp`
- `V2/Asset Control.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `MSFLXGRD.OCX`
  - `TABCTL32.OCX`

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/AssetControl`.
Company names in project files: ADI Limited, Dave Robinson.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
