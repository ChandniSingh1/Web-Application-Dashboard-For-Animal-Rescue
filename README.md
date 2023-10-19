# Web-Application-Dashboard-For-Animal-Rescue
Chandni Singh
Grazioso Salvare Dashboard README
Project Description
This README accompanies the Grazioso Salvare Dashboard project, providing documentation and instructions for reproducing the project. The dashboard serves as a data visualization tool for an animal shelter, providing filterable data, interactive tables, charts, and a geolocation map for animal rescue planning.
Required Functionality
The required functionality of the project includes:
•	Displaying a logo image at the top of the dashboard.
•	Filtering and displaying data from a MongoDB database based on rescue types.
•	Providing an interactive data table that allows sorting, filtering, and selecting multiple rows.
•	Generating a pie chart showing the distribution of animal breeds based on the selected data.
•	Displaying a map with markers for selected animals' geolocations.
Tools Used
Tools and Technologies
•	Python: The primary programming language for development.
•	Dash: A Python web framework for building web applications, which provides the view and controller structure for the dashboard.
•	Dash Leaflet: A library for integrating interactive maps in Dash applications.
•	Pandas: Used for data manipulation and handling.
•	Plotly Express: Used for creating interactive data visualizations.
MongoDB
MongoDB was chosen as the model component for the following reasons:
•	JSON-Like Documents: It stores data in a flexible JSON-like format, which aligns with Python dictionaries and is easy to work with.
•	Schema Flexibility: MongoDB's schema-less design allows for easy adaptation to changing data structures, which is common in real-world applications like animal shelters.
Dash Framework
The Dash framework was selected for creating the web application because of its simplicity and flexibility. Dash provides a Pythonic approach to web development and seamlessly integrates with Plotly for data visualization. It enables the creation of interactive web-based data applications without extensive knowledge of web development technologies.
Project Steps
To complete this project, the following steps were taken:
1.	Data Retrieval: Data was retrieved from a MongoDB database using the pymongo library, which allows Python to interact with MongoDB.
2.	Dashboard Design: The project's layout was designed using Dash HTML and Core Components, including a logo image, radio button for filtering, a data table, a pie chart, and a geolocation map.
3.	Data Filtering: A callback function was created to filter and update the data table based on the selected rescue type.
4.	Interactive Data Table: The data table was designed to support features such as sorting, filtering, selecting multiple rows, and displaying selected columns.
5.	Pie Chart: Another callback function was created to generate and update the pie chart based on the selected data.
6.	Geolocation Map: The geolocation map was implemented using the Dash Leaflet library, with markers and popups for selected animals.
7.	Testing and Deployment: The dashboard was tested to ensure all functionality was working as expected. Screenshots or screencasts were taken to document the project's completion.
Challenges
During the development of the Grazioso Salvare Dashboard, several challenges were encountered:
•	Data Filtering Logic: Implementing custom data filtering logic based on rescue types required a thorough understanding of MongoDB query structures and the PyMongo library.
•	Interactive Map Integration: Integrating an interactive map with geolocation markers was complex and required understanding of the Dash Leaflet library.
•	Responsive Design: Ensuring that the dashboard was responsive across different devices and screen sizes was a challenge, but it was addressed through CSS styling.
•	Data Visualization: Creating interactive data visualizations and ensuring their responsiveness on the dashboard required knowledge of Plotly Express and the Dash framework.
These challenges were overcome through careful research and experimentation. Here are a few screenshots of the completed dashboard: 

