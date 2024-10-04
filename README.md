# Interactive Map Application

This is an interactive map application that allows users to plan driving routes with multiple stops, including draggable routes, customizable stop durations, and real-time travel calculations. Users can save and load routes, calculate travel time, and display the total trip duration in both minutes and "hours and minutes" format. The application also provides a summary of travel distance, travel time, and stopover time. Presently, the app is set up to operate as a local html file and requires a Google Maps Platform API Key. Future versions will include online access.

## About
This is a very simple app. I am sharing it in hopes of building on it and building connections and community. I chose the AGPLV3 license as I am also working to build a very comprehensive Real Estate Appraisal analysys software that I would also like to have all or part built in an open-source copy left environment. Because of the commitment required and the limited number of users, I don't believe a fully open-source license will suit that application. So I am just experimenting with this mapping application for fun really. For transparency, this was built using ChatGPT. I have zero, or almost zero, relative coding experience. I do have assistants with a variety of skills, but this is my own little mini-project that I started on a whim.


## Features
- **Draggable Routes**: Users can manually drag and adjust the routes on the map.
- **Customizable Stops**: Add multiple stops with custom stopover durations.
- **Real-Time Calculations**: Automatically calculate travel time, stop durations, and total trip duration.
- **Save and Load Routes**: Save your routes to local storage and load them for future use.
- **Detailed Summary**: Provides a summary of total travel distance, total travel time, stopover time, and total trip duration in an easy-to-read format.
- **Internet required** for initial loading. Once loaded, the map can be viewed while start times, and stopovers can be updated even if there is no internet connection.

### Requirements
To run the application, you need:
- A Google Maps API key with the **Maps JavaScript API** enabled.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/interactive-map-app.git
   cd interactive-map-app
   
2. Find and replace "YOUR_NEW_API_KEY&libraries=places" with your API *If you intend on using this anywhere other than your own machine ensure you take steps to protect your API.
3. Once you have replaced your API save the file as an HTML
4. Open the HTML

## Usage Instructions
1. After opening the HTML in your browser, Enter a Route Name *This will be used later to re-load. Choose a unique name each time as it will create duplicates (*the current version does not overwrite so you will just end up with multiples with the same name).
2. Enter the start time. *Future versions should have a start date and time to better utilize Google Maps traffic flow estimations. This is experimental as I am not certain how it handles offset start times.
3. Enter Origin and Destination addreses *They can be the same *I am not sure how it handles "Home addresses so you may need to choose a neighbouring address if your home or work destinations are already set in Google.
4. Add in new stops. Currently, auto address search is not enabled so I would suggest using a separate Google Maps tab or browser window to search the correct address and then copy pasting. You may wish to preplan a route in the default Google Maps page and then copy paste over each dress, and then add in your stopover duration. You can re-order in the app, but I find the Google version a little smoother with auto updates.
5. Once addresses are added hit the CALCULATE ROUTE button, and if you are happy, hit SAVE ROUTE
6. Once you have saved a route, you can re-load a route from the drop-down box and hit CALCULATE ROUTE again or add or edit stops then resave as a new name. *After loading a route, you will need to add the start time and if you want to re-save it, add the Route name at the top again.

***Currently, the saved routes are stored in your browser cache. For future updates, we could look at alternatives for more permanent storage that will avoid the inevitable loss due to clearing your browser cache.**

   
