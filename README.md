# Linux Dynamic Wallpapers
<b>Dynamic wallpapers like MacOS for Linux</b>

Tested on Manjaro Gnome 20.2.1

<b>INSTALLATION:</b>

1. download package:

   if you already installed this package, remove previous package before updating
   
       sudo rm -r /usr/share/backgrounds/Dynamic_Wallpapers
       
   clone git repository:
   
       cd ~
       git clone https://github.com/saint-13/Linux_Dynamic_Wallpapers.git
       cd Linux_Dynamic_Wallpapers

   or download package from www.gnome-look.org/p/1499429/:
       a. extrate package
       b. go to extracted folder, right click and open terminal

2. move Dynamic_Wallpapers folder to /usr/share/backgrounds/

       sudo mv Dynamic_Wallpapers /usr/share/backgrounds/
       cd ~
       sudo rm -r Linux_Dynamic_Wallpapers

3. install gnome-tweak-tool.

    Arch:

       sudo pacman -S gnome-tweaks

    Ubuntu:

       sudo apt install gnome-tweaks

4. open gnome tweaks and select xml file. 

    e.g: select : /usr/share/backgrounds/Dynamic_Wallpapers/Mojave.xml
    Warning: if wallpaper does not show properly, you need to change all files and folder's permission in /usr/share/backgrounds/Dynamic_Wallpapers from root to your username

<img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Screenshot%20from%202021-03-30%2019-45-07.png" width="512">

5. (optional) : you can install [Night Theme Switcher](https://extensions.gnome.org/extension/2236/night-theme-switcher/) extension for gnome shell to Automatically toggle your light and dark theme.

6. enjoy!

<b>SCREENSHOTS:</b>

<table>
  <tr>
    <th>Surface</th>
    <th>SurfaceBreeze</th>
    <th>BigSur</th>
    <th>BigSurV2</th>
  </tr>
  <tr>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Screenshot%20from%202021-04-07%2015-11-33.png" width="256">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Screenshot%20from%202021-03-31%2001-26-13.png" width="256">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Screenshot%20from%202021-03-30%2020-02-39.png" width="256">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Screenshot%20from%202021-03-30%2019-06-30.png" width="256">
    </td>
  </tr>
  <tr>
    <th>Mojave</th>
    <th>MojaveV2</th>
    <th>Minimal Mojave</th>
    <th>Catalina</th>
  </tr>
  <tr>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Screenshot%20from%202021-03-30%2018-19-54.png" width="256">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Screenshot%20from%202021-03-30%2018-20-14.png" width="256">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Screenshot%20from%202021-03-30%2018-19-31.png" width="256">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Screenshot%20from%202021-04-07%2016-43-54.png" width="256">
    </td>
  </tr>
</table>
