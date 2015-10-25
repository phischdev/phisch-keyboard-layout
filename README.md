## phisch keyboard layout

![alt tag](https://raw.github.com/phischdev/phisch-keyboard-layouts/master/layout.png)

####Ubuntu
1.) copy the file _phisch-de_ into **/usr/share/X11/xkb/symbols**<p/>
2.) open **/usr/share/X11/xkb/rules/evdev.xml** and insert
  ```xml
  <layout>
    <configItem>
      <name>phisch-de</name>
      <shortDescription>Ph</shortDescription>
      <description>German (phisch)</description>
      <languageList>
        <iso639Id>ger</iso639Id>	
      </languageList>
    </configItem>
    <variantList/>
  </layout>
  ```
  into `<layoutList>...</layoutList>`<p/>
3.) run **sudo dpkg-reconfigure xkb-data**
<br/>
<br/>
####Windows
run **/Windows/phisch/setup.exe**
