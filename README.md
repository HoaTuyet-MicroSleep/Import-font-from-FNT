# Import-font-from-FNT
A Program can import font FNT to other FNT file

"File Import" is a directory of file which have characters you want import
"File Target" is a directory of desination file
"Start range import (UTF-16)": As the name, it is starting point you want to import, check your UTF-16 code of character on internet
"End range import (UTF-16)": it is the last character you want to import



Example: I have Vietnamese characters in "gameRA2VN.fnt" at location "D:\Sleep\gameRA2VN.fnt", and I want to move them into "game.fnt" at location "D:\PhobosSupplementaries-develop\ImprovedFont\game.fnt". With UTF-16 Vietnamese character code from 0x1EA0 to 0x1EF9. It will be like this:

File import: D:\Sleep\gameRA2VN.fnt
File targer: D:\PhobosSupplementaries-develop\ImprovedFont\game.fnt
Start range import (UTF-16): 1EA0
End range import (UTF-16): 1EF9
