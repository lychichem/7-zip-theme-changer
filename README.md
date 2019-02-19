# 7-zip-theme-changer
Resource Hacker Scripts to change 7-zip's default ugly theme. Just work for Windows. No more need for .Net 3.5 as 7ztm does.
# How to use
1. Download this repo and change the path in filetype.txt and toolbar.txt.   
2. Download a 7-zip theme anywhere (like deviantart), here I used the theme in 7-zip as an example. NOTE: If your theme lacks some of the files you have to kEEP the sample resource in folder. This espicially happens for filetype icon. And please change the name of all theme resources according to this example or the script will not work properly.   
3. Download ResourceHacker portable and release resourcehacker.exe.   
4. Copy resourcehacker.exe to filetype/toolbar folder if you want to change them.   
5. Run cmd/powershell as administrator, cd to the folder where resourcehacker is located, then input `resourcehacker.exe -script [The txt scriptname in this folder]`   
6. Copy the patched file to the path of origin files to replace them.
7. Enjoy!
