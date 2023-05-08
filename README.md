# Procak.Szymon.RoutePloy.Py
This program is the updated version of the original Route Plotting Program therefore it is now named Procak.Szymon.RoutePloy.py (!!VERSION 2!!) please ensure you are viewing the updated program.
The updated version addressess various issues which have been located after a more thorough run through and picked up errors during the evaluation of the program.
Namely, picked up errors which occured including the program not displaying the 12x12 grid once the user entered the first (Route001.txt) file and only showed that the movements from the original position.
The second issue was that the program did not display a message stating that the route is outside of the 12x12 grid.

Therefore, these issues I now believe are rectified or at least, seem to be regardless of whether a wrong input file is entered or a direction is given which goes outside of the 12x12. Perhaps adding more Route files with varying directions would actually test the program for it to distinguish whether the "wrong" or "deliberately wrong" route files go outside of the 12x12 grid instead of only having 3 route files with simple instructions. 

Thus, the following improvments have now been made:
1. A 12x12 grid is displayed upon entering Route001.txt file
2. Program displays a messsage stating that the Route is outside of the 12x12 grid

The following additions have also been made to improve the overall program functionallity, ease of use and extra caviats which I beleive make it more robust:
1. More time.sleep functions added to add some breaks between the programs tasks and add more authenticity 
2. Program now allows diagonal movement should it require it (by adding additional compass points such as NE,NW etc..)
3. Program now utilises a more visual representation of the drone movment by using directional arrows to show the travel path. This has been changed from originally displaying X markers which may have confused the user as to which direction the drone is travelling in and therefore ending up.
4. A loading bar is included as a neat addition whilst the program is running

In conclusion the program successfully operates from the route files and shows the direction and ending position of the drone by using all 3 Route files.


