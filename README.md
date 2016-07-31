# sketchicon
Create your own icon library

Managing icons in a big team can be messy. Providing a style guide doesn't suffice. A library is thus needed for all icons used across your team.

Here is an example with "Material Design icons" in black and white. 
https://design.google.com/icons/
 
# How to use :
</br>
1. Draw a rectangle
</br>
2. Run the plugin from the Plugins menu or "cmd+shift+m"
</br>
3. Type the name of the icon (if there is a space between words, replace with "_")
</br>
4. Choose the color
</br>
5. Tadaaa

# How to customize the plugin :
</br>
1. Export all the icons you use in all colors needed. Make sure you export them at ~3x the size you usually use in your artboards. Make different folders for different colors. And export icons with name as "ic_layername.png".
</br>
2. Go to Plugins Menu -> Manage Plugins...
</br>
3. Click the "gear" icon at the bottom -> "Show Plugins Folder"
</br>
4. Right Click "Icon Library" -> "Show package contents"
</br>
5. Go to Content -> Resources
</br>
6. Replace the icons you made in this folder
</br>
7. Open "script.cocoascript" in any text editor
</br>
8. Edit the function at line 82 with the folders you have.
</br>
9. Tadaaa

This plugin uses pngs instead of svgs which is useful for teams which have a set of icons and want quick access and remove the chance of duplications of icons. 
 
</br>
Download iconfetcher.sketchplugin.
</br>
Unzip the archive
</br>
Double-click the .sketchplugin file to install it
