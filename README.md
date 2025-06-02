Input

The application collects user input through four main tabs. In the AddCity tab, users enter the name of a city. In the City screen, users can input location names and descriptions for a selected city. The AddCountry tab allows users to input the name of a country along with its currency. These inputs are taken through text fields and submitted via buttons.

Process

Upon receiving input, the app updates the internal state using the useState hook. Each entry—city, location, or country—is stored in its respective list. Navigation between screens is handled using a combination of React Navigation's Bottom Tab and Native Stack Navigators. Data is passed as props between screens to ensure consistency and allow real-time updates.

Output

The outputs are dynamically rendered lists of cities, locations, and countries. The Cities and Countries tabs display the stored data. The City screen shows the locations tied to each city. All updates are immediately visible to the user.

