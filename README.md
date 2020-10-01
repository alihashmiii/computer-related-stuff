# computer-related-stuff
things that are important and can save time

### To change multiple file names in Windows: open Powershell and cd into the folder, then type

 `get-childitem *.tif | foreach { rename-item $_ $_.Name.Replace("Mask","") }`
