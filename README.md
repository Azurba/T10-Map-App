# T10 map app

# About

This app was developed as a semester-based project for the class Software Engineering (CS314), taught by Dave Matthews, on Fall 2021. This was a team project and five students were responsible for developing this app.

***IMPORTANT:*** currently, the app is only able to run on CSU's server (black-bottle.cs.colostate.edu) which can only be accessed inside the CSU network.

***IMPORTANT:*** The code for this app will not be public in GibHub to avoid possible plagiarism from future students about to take the class. **However, the code will be shared/available upon request only**.

# Team information

| Last Name |First Name | CSU eID | GitHub username |
| --- | --- | --- | --- |
| Daknis | Will | daknis | willrd3 |
| Holland | Trevor | tjhollan | tjhollan |
| Pimenta Giudice | Joao | joaop | Azurba |
| Recor  | Daniel | drecor | Sleek-Day |
| Snyder | Ian | isnyder | Iansnyder |

# Introduction

The main idea of this software is to offer the user an easy way to plan a trip, similar to what Google Maps or Waze does. The app was divided in 9 epics, each of which was a request from the client. Epics will be described below.

The app was designed to fit smoothly in mobile and computer screens, as seen in the video below. For the purpose of this file, the videos were recorded in computer screens only. Use fullscreen videos for optimal quality.

https://user-images.githubusercontent.com/58566178/146843499-bb06dbde-b14c-434c-b282-7079db34015f.mp4

# Epics

# 1 - About

The user wanted to know more about the team that built the application.

We provided the user with information about the team and the people on the team such as:
- An image and mission statement for the team.
- An image, name, and short biography for each team member.

https://user-images.githubusercontent.com/58566178/146843367-efad3656-c964-4d1e-bc2c-1134717fc2f3.mp4

# 2 - Find Places

The user wanted to find places to visit that match a simple string to add to their trip. This includes:
- see a list of matching places and their details
- be able to select one or more of these places to add to their trip.
- use the protocol find feature to implement these requests.
- send valid find requests to the configured server.
- the server should support find requests.
- Use progressive disclosure for the list of places and the details for places to help the user easily find what they are looking for.

https://user-images.githubusercontent.com/58566178/146844249-c45b3534-94e6-42dd-b29f-1f3b07270791.mp4

# 3 - Where am I?

The user wanted to add his/her current location to the trip.

https://user-images.githubusercontent.com/58566178/146844367-cf0e4cf2-7eb4-422e-bf81-2d7ad38e2f57.mp4

# 4 - Distances

The client wanted to know the distance between the places in their trip and the cumulative trip distance at each place in the trip. 
- the trip includes a return leg to the starting point
- use miles for the units with an earth radius of 3959
- Support the protocol distance feature on the client and server.

https://user-images.githubusercontent.com/58566178/146844468-f4fba70c-6ea3-4c2c-bf9c-025db9583926.mp4

# 5 - Save file, Load file and Trip name

**SAVE**

The user wanted to be able to save their trip.
- in a format they could load back into this or other applications
- in a format they can display in a spreadsheet or similar tool
- Files are saved in the local filesystem.

**LOAD**

The user wanted to load a previously saved trip that is stored on their system. JSON and CSV formats were choosen for this epics.

**TRIP NAME**

The user wanted to add a name to the trip

https://user-images.githubusercontent.com/58566178/146844725-b160c3a6-d588-4edc-bbcd-63e3189b5ba8.mp4


# 6 - Optimize Trip

The user wanted the application to offer a shorter trip to the same destinations if one exists and then let them choose the new trip. Nearest neighbor algorithm was used for this purpose.

https://user-images.githubusercontent.com/58566178/146845047-f054d281-ff8d-45ed-875c-f75f24337604.mp4


# 7 - Highlight Place

The user wanted to select a place in the trip/itinerary list and have it highlighted with a marker on the map.

https://user-images.githubusercontent.com/58566178/146845633-01e3cab8-d3eb-4aa8-8264-40a1474ba1ab.mp4


# 8 - Modify Trip

The user wanted to make changes to the tour by:
- select a new starting location while maintaining the order of the destinations.
- reorder individual destinations.
- Let the user remove destinations.

https://user-images.githubusercontent.com/58566178/146845672-dbcedd00-022a-4feb-8099-821c3e6de230.mp4


# 9 - Where is?

The user wanted to enter a latitude/longitude combination to see where it is on the map.
- The latitude and longitude can be entered in a variety of formats when obtained from other tools.
- The latitude and longitude may need validation -> latitude from -90 to 90 and longitude from -180 to 180
- The map should move the marker to this location.
- The user should be allowed to add the marker to the trip.

https://user-images.githubusercontent.com/58566178/146845788-02fab947-bfb5-49aa-8d7e-da9cc8120b25.mp4
