# Starling Service Checker downloads

This is the official public download repository for Starling Service Checker Windows installers and its blank coverage workbook.

## Download

Open [Latest release](https://github.com/coolool/StarlingServiceChecker-Releases/releases/latest), then download:

- `StarlingServiceChecker-Setup-<version>.exe` to install the application; and
- `StarlingServiceChecker-Coverage-Template.xlsx` if you need a blank coverage workbook.

No GitHub account, Excel installation, separate .NET runtime, Git, or developer tools are required to install and use the application. Excel or another compatible spreadsheet editor is needed only if you want to fill in the blank workbook template.

## Blank coverage workbook

The template contains the exact `Tower Coverage` and `Fibre Coverage` worksheets and headers required by the application. It contains no sample coverage or company data.

Keep both worksheet names and the header row unchanged. Enter one tower or fibre range per row beginning on row 2, save the completed workbook with your own filename, and choose it inside Starling Service Checker.

## Windows warning

The installer is intentionally unsigned. Windows may show **Unknown publisher** or **Microsoft Defender SmartScreen protected your PC**.

If your company permits unsigned applications, select **More info**, confirm the application name is **Starling Service Checker**, and select **Run anyway**. If that option is unavailable or company policy blocks installation, stop and contact your IT team. Do not disable Windows security controls.

Only download the application from this repository. Each release includes:

- the Windows installer;
- the blank coverage workbook template;
- a SHA-256 checksum file; and
- a release manifest containing the version, checksum, update URL, and source-commit provenance.

This repository intentionally contains no application source code, populated coverage spreadsheet, Google API key, customer information, database, or backend data.
