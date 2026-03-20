# VAG LongCoder-Neo
Advanced VAG Long Coding helper with modern UI and Themes, fully compatible with VCDS.  
Tested on Windows 11 x64, will not work on windows 7.  
.NET 10 Desktop Runtime required — download from https://dotnet.microsoft.com/download/dotnet/10.0 — pick "Run desktop apps" → Windows x64  
## Features:  
* Modern UI designed for Windows 11 / 10.  
* Hex bytes are uniformly spaced to help understand them better.  
* Better highlighting of the selected Hex Byte.  
* Copy and Paste buttons for easier coding. 
* Supports custom Label files (*.lbl, *.xpl)
* Sizeable UI - Small and Large.  
* Supports themes - Includes 4 themes, Light and Dark modes.  
* Display the currently selected controller number and its description from VCDS.  
* Fully drop-in replacement of the included LCode in VCDS.  
* Supports Keyboard shortcuts of LCode.  
## License
  This project is licensed under a proprietary license. See [LICENSE](LICENSE) for details.
## Usage:
  You can use the LongCoder.exe as a standalone program to edit long coding of the VAG control modules or use it with VCDS completely replacing the included LCode.exe  
  ### For Stanalone use:  
  * Paste the long coding HEX string in the program using the "Paste" button and edit as you like.  
  * Copy the edited final HEX string using the "Copy" button.  
  * When the program starts, it automatically loads the HEX string from the clipboard if valid coding string is present.  
### For use  with VCDS: 
  * Copy the LongCoder.exe to the installation directory of VCDS (C:\Ross-Tech\VCDS)  
  * Rename the included "LCode.exe" file to "Lcode.exe.bak"  
  * Rename the "LongCoder.exe" to "LCode.exe" and it should work seamlessly with VCDS. 
  
  
  Please consider donating to support the development:  
BTC address: bc1qzn9tzpkk9fryh5srhgxhghxy2d7ql9usz23p9e
