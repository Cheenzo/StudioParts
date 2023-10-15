# StudioParts

This repository was setup in order to have a common place for the Studio community to:

1. Share missing parts from Studio
2. Share updated or fixed parts from Studio
3. Centralize and give visibility on the new or updated parts that are pending review for integration by Studio development team

If you want to read more on how the Studio part library works, you can check out this [FAQ](https://forum.bricklink.com/viewtopic.php?t=6368) in the Studio forum.

# Access

This repository is public and allows anyone to download the files to integrate them by themselves in Studio with Part Designer.

If you want to contribute sharing your own parts in this repository, you can do so by sending your contributions by e-mail to cheenzo (at) gmail.com

# Folders

## Submitted to Studio team

A folder including all parts submitted to the Studio team that are pending to be reviewed by the team for being included in a future release of Studio:

<https://github.com/Cheenzo/StudioParts/tree/main/Submitted%20to%20Studio%20team>

## Other parts

A folder including all parts not submitted to Studio team because they are not (yet?) considered as being potential candidates for different reasons (Duplo, flexible parts, wearable parts, unofficial Lego parts, etc.):

<https://github.com/Cheenzo/StudioParts/tree/main/Other%20parts>

# How to use these parts

In these folders you will find .dat, .col and .conn files:

- .dat files contains the part 3D model and colors,
- .col files contains information for Studio to manage collisions,
- .conn files contains information for Studio to manage connections with other parts.

To import them into Studio, you need to put the files in the appropriate folders
(you may have to change your settings so hidden folders and files are
visible):

- For Windows, Local Disk > Users > [username] > AppData > Local > Stud.io > CustomParts
- For macOS, Local Disk > Users > [username] > .local > share > Stud.io > CustomParts

It might happen that CustomParts does not exists yet, in that case create it as well as 3 subfolders inside:

- parts
- connectivity
- collider

Place:

- .dat files in the parts folder,
- .conn files in the connectivity folder and
- .col files in the collider folder.

Then launch Studio and switch your building palette from Master to Custom Parts to access the part you just added.

You will also find .part files that can be opened with PartDesigner and then exported to Studio.

# Licences

This repository relies on the Creative Commons Attribution Licence 2.0

This repository is made possible by the LDraw Parts Library.
LDraw™ is a trademark owned and licensed by the Estate of James Jessiman.
Visit the official LDraw website at <https://www.ldraw.org>

LEGO and BrickLink are trademarks of the LEGO Group, which does not sponsor, endorse, or authorize this site.

Visit the official Lego website at <https://www.lego.com>

Visit the official BrickLink website at <https://www.bricklink.com>

Download Studio at <https://www.bricklink.com/v3/studio/download.page>
