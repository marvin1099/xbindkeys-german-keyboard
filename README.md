# Xbindkeys-German-Config

This is a "third layer" config for linux systems without being a actual third layer.       
It will translate ctrl + alt + (keys for German third layer) to their corresponding keys.       
For example "ctrl + alt + q" to "@"      

# Compatibly
This Config should work on systems based on: Arch, Debian, Red Hat      
This config works on all of them because it uses Software that is available on all of these systems.

# Installation
<table>
<tr>
<td> Run in shell </td>
<td> On Arch based systems </td> 
<td> On Debian based systems </td> 
<td> On Red Hat based systems </td> 
</tr>
<tr> 
<td> 1. </td>
<td> sudo pacman -S curl xbindkeys xdotool </td> 
<td> sudo apt install curl xbindkeys xdotool </td> 
<td> sudo yum install curl xbindkeys xdotool </td> 
</tr>
<tr> 
<td> 2. </td> 
<td> run in terminal: curl -o ~\.xbindkeysrc 'https://raw.githubusercontent.com/marvin1099/xbindkeys-german-keyboard/main/.xbindkeysrc' </td> 
<td> Same as Arch </td> 
<td> Same as Arch </td> 
</tr>
<tr>
<td> OR 2. </td> 
<td> manualy download the ".xbindconfig" file from 'https://raw.githubusercontent.com/marvin1099/xbindkeys-german-keyboard/main/.xbindkeysrc' and put it in to your home folder </td>
<td> Same as Arch </td> 
<td> Same as Arch </td>  
</tr> 
<tr>
<td> 3. </td>
<td> run in terminal: xbindkeys </td> 
<td> Same as Arch </td> 
<td> Same as Arch </td> 
</tr>
</table>
