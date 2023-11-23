<p align=center>SCRIPTER.</p>

<p align="center">
  <img src="https://github.com/gregoiredehame/kata/assets/74637340/011307af-4f80-4070-a38f-16da3f6e48c8">
</p>

<p align=center> A Code Editor QWidget for Autodesk Maya.</p>

 Preview
-----------------------
![script](https://github.com/gregoiredehame/scripter_public/assets/74637340/922a287a-1804-41ab-9905-4a8eb067e130)

 Description
-----------------------
this script editor is highly inspired by the famous charcoalEditor and has been made for kata auto rigging system.
this include: 

- auto saving temp files
- script execution
- output window ( python / mel )
- syntax highlighting ( output and input )
- multiple workspaces
- code auto-complete
- colors user preferences
- support both maya/mel
  
the application can boot on a specific directory who allowed multi artists to work on the same location/project


 Supported Maya Versions
-----------------------

 scripter supports two major versions of Maya:
- 2022
- 2023

 Installation
-----------------------
 
 Installation guide:
 - Download scripter repo, and past it into your maya system paths ( ex: scripts folder )
```py
from scripter import main
main.script_manager(area=None, show_outputs=True, show_workspaces=True, directory=None)
```

scripter is developed and maintained by Gregoire Dehame.
