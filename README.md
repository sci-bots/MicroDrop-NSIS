# MicroDrop-NSIS
NSIS script for creating MicroDrop 3 Installer

## Setup Instructions:
1. Run Electron Packager:
```bash
 cd microdrop/packages/builder
 yarn packager
```
2. Rename packager/MicroDrop-* to packager/MicroDrop
3. Run Miniconda 32bit Installer
4. Select Install Globally, and change path to: packager/MicroDrop/miniconda

5. Create 7zip archive (right click -> 7-Zip -> Add to "MicroDrop.7z"
6. Copy MicroDrop.7z to MicroDrop-NSIS directory

7. Run Make NSIS Compile tool
