# Ancient Travel Tips
## Basic Details
### Team Name: Ctrl+Alt+Defeat
### Team Members:
  - Sona Mariya Siju [SJCET,Palai]
  - Aavani V V [SJCET,Palai] 
  - Cherian Shaji [SJCET,Palai]
  
### Project Description
  This project offers users a historical travel experience by providing tips and suggested itineraries tailored to various ancient and historical time periods and locations. Users can select a time period (such as Medieval Europe, Renaissance Italy, or Ancient Egypt) and a specific city or place (like Paris, Cairo, or Rome) relevant to that era. Once a location and period are chosen, the program displays helpful travel tips and a suggested itinerary for that historical context, giving users an immersive glimpse into how they might travel in these past worlds.
### The Problem(that doesn't exist)
  People face the difficulty in authentically experiencing ancient locations
### The Solution(that nobody asked for)
  We've developed a website that enables users to choose a time period and location, offering tips and suggestions for exploring that destination which provides them with a realistic experience.
## Technical Details
### Languages Used
  - HTML
  - CSS
  - Java Script
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



    
