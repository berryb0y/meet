Meet app

FEATURE 2: SHOW/HIDE AN EVENT'S DETAILS
As a user I should be able to show/hide an event's details so that I can see an event's details

Scenario 1: An event element is collapsed by default
*Given the user is on the main page
*When nothing is selected
*Then the event details will be collasped
Scenario 2: User can expand an event to see its details
*Given the user is on the main page
*When a user clicks "show details"
*Then the event details are shown
Scenario 3: User can collapse an event to hide its details
*Given the user is looking at event details
*When a user closes the "show details" window
\*Then the user is back on the main page

FEATURE 3: SPECIFY NUMBER OF EVENTS
As a user I should be able to specify the number of events so that I can only see a specific amount

Scenario 1: When user hasn’t specified a number, 32 is the default number
*Given the user is on the main page
*When the user hasn't selected a different quantity of events
*Then 32 events will be shown
Scenario 2: User can change the number of events they want to see
*Given they are on the main page
*When they click a different quantity of events to be down
*Then the number of events shown will change

FEATURE 4: USE THE APP WHEN OFFLINE
As a user I should be able to use the app when offline so that my connection won't have a full impact on my quality

Scenario 1: Show cached data when there’s no internet connection
*Given the user is on using the application
*When connection is lost
*Then the cached data will be shown
Scenario 2: Show error when user changes the settings (city, time range)
*Given the user is using the application
*When the user settings (city, time range)
*Then an Error will be shown

FEATURE 5: DATA VISUALIZATION
As a user I should be able to see see a chart with the number of upcoming eventsin each city

Scenario 1: Show a chart with the number of upcoming events in each city
*Given The user is on the main page
*When they want to see if events are coming
\*Then they will see a chart with how many events are coming
