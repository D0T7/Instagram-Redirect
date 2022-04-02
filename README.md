Instagram-Redirect.<br/><br/>

Requirements:<br/>
Userscript manager([Violent Monkey](https://violentmonkey.github.io/), [Tamper Monkey](https://www.tampermonkey.net/) etc)<br/>

How to Install?<br/>

-Click [here](https://github.com/D0T7/Instagram-Redirect/raw/main/user.script.js) to open the script.<br/>
-Copy the whole script.<br/>
-Click the "+" button in top left corner.<br/><br/>
![Violent Monkey Screen](https://user-images.githubusercontent.com/63301189/161377509-bb90ba89-e386-428c-8982-167b91b9b8c7.png)<br/><br/>
-Click on "New".<br/><br/>
![Add Script Button](https://user-images.githubusercontent.com/63301189/161377567-7c45ea99-b353-4b97-8cae-5730e0eb79a0.png)<br/><br/>
-Paste the Script that you copied.<br/>
-Save.<br/>

Want to change the anonymous viewer/frontend ?<br/><br/>
You can change the viewer/frontend that this script redirects to by changing "url" and "key" variables.<br/>
```
  let url = "url";
  let key = "key"; 
```
<br/><br/><br/>
Example:<br/><br/>
If you want to set the redirects to bibliogram.art. <br/><br/>
When opening a profile in bibliogram , the URL pattern is bibliogram.art/u/profilename. <br/>
-Set the "url" to "bibliogram.art" <br/>
-Set "key" to "/u" <br/>
``` 
  let url = "bibliogram.art";
  let key = "/u";
```
-Done<br/>








