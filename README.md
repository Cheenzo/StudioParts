# StudioParts
This repository was setup in order to have a common place for the Studio community to:
1. Share missing parts from Studio
2. Share updated or fixed parts from Studio
3. Centralize and give visibility on the new or updated parts are pending to be reviewed for integration by Studio development team

# Access
This repository is public and allows anyone to download the files to integrate them by themselves in Studio with Part Designer.
If you want to contribute sharing your own parts in this repository you can do so by send your contributions by e-mail to cheenzo (at) gmail.com

# Notes / How to use these parts
For now the repository is composed of two major sections:
1. One folder including all parts created by Andrei (ArkyRomania) and submitted to Studio team
https://github.com/Cheenzo/StudioParts/tree/main/Parts%20created%20by%20Andrei
You will find in this folder and subfolders .part files that can be opened with PartDesigner and then exported to Studio.

2. One section including all parts submitted by Vincent (Cheenzo) to Studio team
https://github.com/Cheenzo/StudioParts/tree/main/Submitted%20to%20Studio%20team
In this folder you will find 3 different folders:
- "New parts" folder contains all new parts missing from Studio
- "New patterns" folder contains all new parts including patterns missing from Studio
- "Updated parts" folder contains all parts already in Studio but having something to be fixed (either missing connectivity info or wrong 3D model or wrong pattern, ...)
In these folders you will find .dat, .col and .conn files:
.dat files contains the part 3D model and colors
.col files contains information for Studio to manage collisions
.conn files contains information for Studio to manage connections with other parts

To import them in Studio you need to put the files in the appropriate folder (you may have to change your settings so hidden folders and files are visible):
    - For Windows, Local Disk > Users > [username] > AppData > Local > Stud.io > CustomParts
    - For macOS, Local Disk > Users > [username] > .local > share > Stud.io > CustomParts

Place .dat files in the parts folder, .conn files in the connectivity folder and .col files in the collider folder.

Then launch Studio and switch your building palette from Master to Custom Parts to access the part you just added 

# Licences
This repository relies on the Creative Commons Attribution Licence 2.0

This repository is made possible by the LDraw Parts Library.
LDraw™ is a trademark owned and licensed by the Estate of James Jessiman.
Visit the official LDraw website at https://www.ldraw.org

LEGO and BrickLink are trademarks of the LEGO Group, which does not sponsor, endorse, or authorize this site.
Visit the official Lego website at https://www.lego.com
Visit the official BrickLink website at https://www.bricklink.com
Download Studio at https://www.bricklink.com/v3/studio/download.page
