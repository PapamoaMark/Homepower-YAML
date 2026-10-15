Create a Dashboard in the side navigation bar
=============================================
Settings>Dashboards
Click Add dashboard button on lower right
Click "New dashboard from scratch"
Give your new dashboard a Title.  Icon is optional, URL self populates from your title, but you can override if you wish
  Ensure Add to sidebar is on, the click "Create"
  
You now have a new blank dashboard item.  Now to import a YAML file
  Click in your new dashboard item.  Click on the pencil icon at the top right. This opens your dashboard item in edit mode.
  You have a blank "tab" called Unnamed view.  Click the pencil icon to the right of the tab name.  Or click the + icon to create a new tab.
  In the View configuration screen, click the tripple dot menu at the top right and click "Edit in YAML"
  Delete any existing YAML code and paste in the contents of your YAML file, click Save.
  You should now see your new dashboard. It is still in edit mode, you can tweak some of the settings from here is you wish.
  When finished, click Done at the top right and it is in normal view mode.

Note - if some of the data does not show and has something like "Entity not found" it will be because the data point or sensor (Entity) has a different name in your system.  
You should be able to edit those "cards" and select the correct Entities as appropriate.

Prerequisites:- 
Must have a Home Assistant appliance (lots of ways to achieve this, links in Sean Lewis's instructions).
Must have Sean Lewis's Homepower integration installed.
Link to Sean Lewis's GitHub - https://github.com/seanlewis/openhomepower-hass

Possible gotcha - your system may have some of the sensors named differently, so you may have to edit the appropriate dashboard view and select the sensor entity from your system to get the correct one.
