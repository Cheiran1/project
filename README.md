# ChronoQuest
## Basic Details
### Team Name: Ctrl+Alt+Defeat
### Team Members:
  - Sona Mariya Siju [SJCET,Palai]
  - Aavani V V [SJCET,Palai] 
  - Cherian Shaji [SJCET,Palai]
  
### Project Description
  ChronoQuest is a unique website designed to support time travelers exploring ancient and historical destinations. With a simple, interactive interface, users can select a specific time period and location, unlocking customized travel advice to help them fully immerse in each era.
For every selected era and place, ChronoQuest provides key insights on how to blend in with the locals, including guidelines on traditional attire, behaviors, and customs. Users receive detailed information on the ruling figures of the time, foods to try, and essential precautions to navigate potential cultural challenges. The site also highlights notable landmarks, marketplaces, and other points of interest for a complete historical experience.
By combining practical travel tips with rich historical context, ChronoQuest is the ultimate tool for anyone looking to explore the past authentically and confidently, making every journey through time as seamless as possible.
### The Problem(that doesn't exist)
  People face the difficulty in authentically experiencing ancient locations
### The Solution(that nobody asked for)
  We've developed a website that enables users to choose a time period and location, offering tips and suggestions for exploring that destination which provides them with a realistic experience.
## Technical Details
### Languages Used
  - HTML
  - CSS
  - Java Script
### Implementation
  - The HTML defines the structure of the webpage, including a dropdown selection for time periods and locations, a button to fetch travel tips, and a section to display the tips and itineraries.
 
 - The CSS provides styling that gives the webpage an ancient, historical feel:
Background: A textured background is added using a paper-like image, creating a vintage look.
Font Styles: Fonts and colors were selected to reflect an ancient aesthetic, with serif fonts and golden accents to create a historical vibe.
Button Hover Effects: Animations on the button make it visually engaging, with scaling and color changes on hover.
Responsive Design: Media queries are included to adjust the layout on smaller screens.

- JavaScript provides the interactive behavior of the page:
Data Structure for Travel Tips: An object, travelTips, stores information about each time period and location, including travel tips and suggested itineraries.
Location Selection Update: When the user selects a time period, JavaScript dynamically updates the available locations in the second dropdown by referencing the locationsByPeriod object.
Travel Tips Display: When the button is clicked, the getTravelTips() function retrieves the tips and itinerary for the selected location and time period, displaying them in a previously hidden <div>.

## Screenshots
### Menu 1

![Screenshot 2024-11-02 151146](https://github.com/user-attachments/assets/338a80b4-0223-4999-aa26-b0674de8c8cf)

* Select a Time Period:
   - The user starts by selecting a historical time period from a dropdown menu, with options like "Medieval Europe," "Renaissance Italy," or "Ancient Egypt."
Based on the chosen period, the website automatically updates the available locations to match that era.

### Menu 2

![Screenshot 2024-11-02 151203](https://github.com/user-attachments/assets/3560ff5a-c74b-4ace-97e7-5892a3428059)

* Select a Location:
   - After choosing a time period, the user can select a specific location within that era (e.g., "Rome" in Renaissance Italy).
This selection helps tailor the travel tips and itinerary to a unique place within the chosen historical context.

### Menu 3

![Screenshot 2024-11-02 151221](https://github.com/user-attachments/assets/5925db68-f8b7-44f2-b61a-b2f9cfd2018c)

* View Travel Tips and Suggested Itinerary:
  - Upon clicking "Get Travel Tips," the website displays relevant travel tips for that period and location, such as appropriate clothing, safety advice, and cultural etiquette.
Additionally, a suggested itinerary for that location is provided, highlighting historical landmarks, traditional activities, and notable sites to visit, giving the user a feel for a day in the life of a traveler from that era.

## Team Contributions
  - Aavani V V : Organized and created the travel tips and itineraries for different periods and locations.
  - Cherian Shaji :  Implemented the JavaScript functions to handle user interaction and dynamically update content.
  - Sona Mariya Siju : Developed the HTML structure and styled the page to reflect an ancient design theme, creating an engaging user interface.



    
