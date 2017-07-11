# Introduction
This repository allows you to install board support for the [Iteaduino Lite](https://www.itead.cc/wiki/Iteaduino_Lite) board, produced by Itead.

## Installation
Assuming you have already installed your board's COM port drivers.

1. Install Arduino IDE (Tested with 1.6.12, other versions may work also)
2. Go to the "File" -> "Preferences" Menu
3. to go the "Settings" tab, and under the "Additional BoardManager URLs" field, insert the following URL:
   [https://raw.githubusercontent.com/udif/ITEADSW_Iteaduino-Lite-HSP/master/package/package_iteaduino_lite_index.json](https://raw.githubusercontent.com/udif/ITEADSW_Iteaduino-Lite-HSP/master/package/package_iteaduino_lite_index.json)
   If there is already another URL, add the URL above, separating it with a comma (,) from the existing URL(s).
4. Under the "Tools" -> "Board: xxx" menu select the topmost option in the scrolling list of boards - "Board Manager".
5. Find "Iteaduino Lite" in the board list (You can filter your search) and select it. Install it by pressing the "Install button"
6. Under the "Tools" menu, select the new "Board: Iteaduino Lite" option.
7. Select your COM port.
8. You may use the board now.

Please check the original Readme file in this directory for more specific information on the LGT8F Hardware Support Package (HSP).
