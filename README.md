# FDAS---Fire-Detection-Alert-System
A croud based fire detection and alert system

The system scans all registerd webcams, until it ditects a fire.
Then it does:

Characterization of Fire,
Identification of fire potential,
Setting the size (it is important to refer to the cover of the fire image in the whole picture - varies according to the angle of the lens and distance, hence the parameter differs from camera to camera, personal) fire vs. fire,
Growth rate = A parameter for separating the Lag BaOmer bonfire from arson and fire
Day / Night - Relating to the radiation intensity between different lighting conditions
 
Algorithm and Tracking -
Once the system detects a suspected ignition, it scans the same camera several times a minute and tries to detect the "fire" growth.
If the same point targets another camera, the system will also prioritize it in the scanning and processing cycle.
If the "fire" does not fall under the category of fire, a yellow message will be sent to the center indicating that there is a fire point. The center can observe, monitor and transfer the point to a green state, which means controlled fire (cases of controlled fire and coordinated with the authorities / firefighters, and so on).
HaMoked can make a decision that this is an arson and move the message to a "red" level. In this case, a "list of points of interest" (hereinafter referred to as "the Authority") also receives the notice.
If the system identifies "ignition", it will immediately notify the Hotline and the Authority, of such warning.
