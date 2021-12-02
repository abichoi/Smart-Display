# Smart-Display
This display is to display infromations on screen in Nier: Automata theme.<br>
**Please load the display in a portrait screen.** <br><br>

This display is divided into 5 sections.

_**Section 1: Clock**_
This section displays the date and time curretly on the bottom left corner.

_**Section 2: Calendar**_
This section displays a google calendar through an iFrame.

_**Section 3: Mission**_
This section is a to-do list. By:
Hovering on the list item: Item background colour turns into a dark color and font colour turns into orange.
Clicking on the list item: This means that task is finished. Clicking it again will toggle it back to unfinished state.
                           Item backkgrounf colour turns into grey and font colour turns into white. The arror on the left turns into a tick.
Clicking on the cross: This will delete the item regardless if the task is finished or not.
Clicking the Submit button: If there are text in the input area, the text will be apppended into the current to-do list. 
                            Otherwise, an alert box will pop up.
                            
_**Section 4: Status**_
This section displays the weather forecast today and the next 7 days from Open Weather Map API.

_**Section 5: Target**_
This section displats the temperature and humidity of the environment and the moisture of the soil fenched from the MQTT server.

_**Other: Dragging**_
Section 3-5 are draggable.

# A screenshot of the smart display
<img src="https://github.com/abichoi/Smart-Display-Nier/blob/main/img/screenshot.jpg" width="80%"/>
