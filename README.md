# degenesisfvtt-artiCSS
### Styling for the Degenesis system of Foundry VTT

# About
I really love how customizable Foundry and the Degenesis system for it is, so I made a quick CSS hack because I love the Artifacts style as well. (shown with Harms Way module loaded). These changes do not touch your main Degenesis system at all, they are CSS overrides done by a module you need, Custom CSS.

![chat](https://user-images.githubusercontent.com/72170114/134515530-f8d89b3e-6de9-4d17-bdaa-64bc81652652.png)
![main](https://user-images.githubusercontent.com/72170114/134515544-d87a5dae-f057-4892-93bd-9b54d298ef92.png)

# How to install
1. Install the Custom CSS Module in Foundry VTT ( https://foundryvtt.com/packages/custom-css )
2. Go to the Module Settings of Custom CSS and click the Custom CSS Rules button
3. Paste the content of the **Degenesis Arti Style.css** file into the Custom CSS Rules window and click save.
4. The Artifacts styling should now be applied to your Degenesis system.

This file contains the Artifacts styling for PC sheets and the Chat Card display. If you just want a part, look for the comment section "/* * Start of Sheet CSS */" and cut there. 

# Customizing
It's possible to relatively easy change the main UI color to something different than the Artifacts Gold. All you need to do is look at the color definitions starting at the **root** code part of the **Degenesis Arti Style.css** code. The Color Definitions comment in the CSS file explains how it works.

The only things currently not easily changeable are the Culture/Concept/Cult Icons and the sheet's lines at the borders.
Examples of changing the main color:

![recolor](https://user-images.githubusercontent.com/72170114/134515554-e4f8cdce-ef1f-424e-ba1d-71d216745c59.png)
![image](https://user-images.githubusercontent.com/72170114/134558099-43db65de-9af2-446f-9a5a-b869b83dcb02.png)
Red style uses the following color codes for example:
    :root {
      --degenesis-red: hsl(0deg 65% 41%);
      --blackred: hsl(0deg 65% 21%);
      --lightred: hsl(0deg 65% 61%);
      --darkred: hsl(0deg 65% 10%);
    }
![image](https://user-images.githubusercontent.com/72170114/134559051-ee4d74db-97bf-4097-838f-408376f41b00.png)
This Chronicler blue style uses:
    :root {
      --degenesis-red: hsl(200deg 35% 41%);
      --blackred: hsl(200deg 35% 21%);
      --lightred: hsl(200deg 35% 61%);
      --darkred: hsl(200deg 35% 10%);
    }

# Disclaimer
not 100% perfect. You can report any bugs or issues here on Github or directly to me on the Degenesis Discord.

# To Do
- Needs fixing: Text Editor field text displayed in black color when editing 

# Credits
- Degenesis Foundry VTT System shown by Moo Man and many other great Devs ( https://github.com/moo-man/DEGENESIS-FoundryVTT )
- Harm's Way content by Chernojack ( https://github.com/dgr-foundry/dgr-harms-way )
- Custom CSS Module by zeel ( https://foundryvtt.com/packages/custom-css )

# License
Licensed under the MIT License terms https://mit-license.org
