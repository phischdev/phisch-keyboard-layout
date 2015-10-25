# phisch keyboard layouts
For Ubuntu and Windows


###Ubuntu
1.) copy the file _phisch-de_ into /usr/share/X11/xkb/symbols<p/>
2.) open /usr/share/X11/xkb/rules/evdev.xml and insert
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
  into ```<layoutList>...</layoutList>```<p/>
3.) run _sudo dpkg-reconfigure xkb-data_

###Windows
run
