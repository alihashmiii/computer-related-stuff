# computer-related-stuff
things that are important and can save time

### To change multiple file names in Windows: open Powershell and cd into the folder, then type

 `get-childitem *.tif | foreach { rename-item $_ $_.Name.Replace("whatever name or character you want to remove comes here","") }` in this example `*.tif` is the fie extension which can be changed to whatever is desired. [source-link](https://superuser.com/questions/236820/how-do-i-remove-the-same-part-of-a-file-name-for-many-files-in-windows-7/578076#578076?s=96b38dbf86d24bbc90407473f8a7acf4)
