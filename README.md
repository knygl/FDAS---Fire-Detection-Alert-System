# FDAS---Fire-Detection-Alert-System
A croud based fire detection and alert system

The system scans all registerd webcams, until it ditects a fire.
Then it does:

Characterization of Fire,
Identification of fire potential,
Setting the size (it is important to refer to the cover of the fire image in the whole picture - varies according to the angle of the lens and distance, hence the parameter differs from camera to camera, personal) fire vs. fire,
Growth rate = A parameter for separating the autorized bonfire from arson and fire
Day / Night - Relating to the radiation intensity between different lighting conditions
 
Algorithm and Tracking -
Once the system detects a suspected ignition, it scans the same camera several times a minute and tries to detect the "fire" growth.
If the same point targets another camera, the system will also prioritize it in the scanning and processing cycle.
If the "fire" does not fall under the category of fire, a yellow message will be sent to the center indicating that there is a fire point. The center can observe, monitor and transfer the point to a green state, which means controlled fire (cases of controlled fire and coordinated with the authorities / firefighters, and so on).
HaMoked can make a decision that this is an arson and move the message to a "red" level. In this case, a "list of points of interest" (hereinafter referred to as "the Authority") also receives the notice.
If the system identifies "ignition", it will immediately notify the Hotline and the Authority, of such warning.

The App!
Based on a smart phone application that reports to a national call center:
The application relies on phone sensors - a compass, a GPS, and a camera.
 
A user who downloaded and installed the application on his or her phone, goes through a short registration process on the site. The registration is intended on one hand to create credibility in reporting and the ability to neutralize flooding and harassment. On the other hand, it will enable the recipients to be rewarded, in letters of thanks, continued rating of the donation, and even in additional evaluation gestures to the point of prizes.
 
Once the application is installed, and the user logs on, it is not used until the critical moment when it detects a suspected ignition.
All he has to do is:
Launch the app (phone icon)
Shoot a photo of the Fire (camera trigered from the app.)
Direct the phone towards the fire (the compass appears, the arrow is fixed and should be directed towards the fire, the circle of directions spinning around it = azimuth)
Press the "Send" key
Now the app is broadcasting:
User ID (app data as recorded)
The direction, as recorded by the compass
Position of the photographer according to the GPS
Image
The data from all users is collected at the national center and
We will send confirmation to the reporter
A message is sent to the  fire department in the reporting area/region, including all the data
The system is waiting for another message from another user for that region (according to GPS data)
Once there are two or more observations, the system calculates an exact place according to the azimuths sent from the observations.
A certified fire alarm (two or more observations) is sent to the call center
