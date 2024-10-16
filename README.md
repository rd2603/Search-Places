#GeoDB Cities Search App

Table of Contents
1. Running the Project
2. Folder Structure
3. Components Overview


1. I was facing some issue with github so I did uploaded zip file.
1.1 Download Zip file.
1.2 Unzip zip file.
1.3 Run NPM INSTALL
1.4 Run NPM start

By these step project will start.

2. Folder Structure
search-places
│
├── public/                   # Static public assets
│   └── index.html            # Main HTML file for the app
├── src/
│   ├── components/           # Reusable React components
│   │   ├── SearchBar.js      # Component for the search bar
│   │   ├── CitiesTable.js    # Component to display city results
│   │   ├── Pagination.js     # Component to handle pagination
│   │  
│   │    
│   │   
│   │  
│   ├── services/
│   │   └── api.js            # Contains API calls to GeoDB Cities API
│   ├── App.js                # Main component, orchestrating the app's flow
│   ├── App.css               # Global styles for the app
│   └── index.js              # Entry point for React
└── package.json 



3.Components Overview


1. SearchBar.js
This component handles the input from the user for the city search term. When the user presses the "Enter" key, the search is triggered.
CSS: SearchBar.css handles the styling for the search input field.

2. CitiesTable.js
Displays the list of cities fetched from the GeoDB API. The results are shown in a tabular format, including the city name and country flag.
CSS: CitiesTable.css handles the table's layout and styling.

3. Pagination.js
Manages pagination by displaying "Previous" and "Next" buttons. It calculates the total number of pages based on the total results and allows the user to navigate between pages.
CSS: Pagination.css styles the buttons and pagination display.

App.js
The main component that pulls everything together. It manages the search term, the list of cities, the current page, the results per page (limit), and handles the logic for calling the API.
CSS: App.css provides global styles for layout and the loading spinner.







