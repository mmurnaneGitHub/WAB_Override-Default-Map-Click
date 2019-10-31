# WAB_Override-Default-Map-Click
Customized files to override defaults for Map Click (MapManager.js), Search Widget Popup (Search_Widget.js), and MyLocation Graphic/Popup (MyLocation_Widget.js) in Esri's Web AppBuilder.

Version 2.14

INSTRUCTIONS:

1. Copy MapManager.js to \jimu.js\MapManager.js

2. Copy MyLocation_Widget.js to \widgets\MyLocation\Widget.js

3. Copy Search_Widget.js to \widgets\Search\Widget.js

4. The rest of the work is done \libs\mjm_ClickReport.js which is unique for each application.

# MOBILE NOTE:
In the Search config file the "showInfoWindowOnSelect" option must be set to false to prevent mobile popups from ignoring generated popup report from mjm_ClickReport.js. 
