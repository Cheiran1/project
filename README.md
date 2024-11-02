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
  There is no travelling guide if you want to experience the ancient times
### The Solution(that nobody asked for)
  We have created a website that allows users to select a time period and a place which will then provide tips and suggestion on how to explore the place.
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


![Screenshot 2024-11-02 151146](https://github.com/user-attachments/assets/338a80b4-0223-4999-aa26-b0674de8c8cf)

## Team Contributions
  - Aavani V V : Organized and created the travel tips and itineraries for different periods and locations.
  - Cherian Shaji :  Implemented the JavaScript functions to handle user interaction and dynamically update content.
  -  Sona Mariya Siju : Developed the HTML structure and styled the page to reflect an ancient design theme, creating an engaging user interface.



    
