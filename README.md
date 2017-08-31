# Lanzarote-photogrammetry-mission

Phase #1 : software UGCS tested with a simple path at Jacobs: the .XML file of the mission is available (name of the file "testOk.xml")

We figured out that in order to use the photogrammetry tool a pro license is needed.

Phase #2: the mission in Lanzarote was subdivided into 29 smaller areas because of the huge size of the studied area. The .XML file is available, its name is "Lanzarote.xml".

For the drone DJI Phantom 4 the limit for a single survey is 99 waypoints (due to its battery power). For this reason, each of the 29 areas contains between 84 and 98 waypoints. If you want to load on the mission all the routes, you have to click on them, one by one, and wait for the yellow circle to become green.

Then, you can upload the mission on the drone.

Phase #3: In order to obtain a lesser degree of uncertainty, some attempts to involve the Reach modules (one RS and one RTK, since the other RTK is not working at the moment) have been made.
A file with the instructions to connect the modules is available ("Emlid info" is the name of the file) but actually this manual seems to follow a different interface from the one we are using. For this reason I wrote another file with all the steps I did with Ramiro ("Home made Emlid" is the name of the file).

