![alt text](https://www.freelogovectors.net/wp-content/uploads/2020/07/hacettepe-universitesi-logo-768x178.png)

# GMT351- Geospatial Data Management Group-5 Final Project Report
---
* Beyza ÖZKAN - 21833369
* Rümeysa Nur KELEŞ - 21833283
* Feyza KARAKELLE - 21833245
---
The purpose of the project we created, is to display the airport points correctly on the base map on the created website, to prepare pop-ups that provide information about the selected airports, to filter the selected data according to countries, and to enable the user to create read update delete applications. HTML, React, JavaScript, and Openlayer were used in the project. Our data will be available at this [website](https://data.opendatasoft.com/explore/dataset/osm-world-airports%40babel/export/?dataChart=eyJxdWVyaWVzIjpbeyJjb25maWciOnsiZGF0YXNldCI6Im9zbS13b3JsZC1haXJwb3J0c0BiYWJlbCIsIm9wdGlvbnMiOnt9fSwiY2hhcnRzIjpbeyJhbGlnbk1vbnRoIjp0cnVlLCJ0eXBlIjoiY29sdW1uIiwiZnVuYyI6IkNPVU5UIiwic2NpZW50aWZpY0Rpc3BsYXkiOnRydWUsImNvbG9yIjoiIzE0MkU3QiJ9XSwieEF4aXMiOiJzb3VyY2UiLCJtYXhwb2ludHMiOjUwLCJzb3J0IjoiIn1dLCJ0aW1lc2NhbGUiOiIiLCJkaXNwbGF5TGVnZW5kIjp0cnVlLCJhbGlnbk1vbnRoIjp0cnVlfQ%3D%3D&location=11,40.09436,33.02731&basemap=jawg.streets). The csv version was uploaded to see the content.

---

The airport project was created by React and Openlayer. React is a widely used JavaScript library. To start, created a html structure head and body set, and added rules to the body for map elements. The base map is selected from Maptiler Cloud and added by OpenLayers. MapTiler Cloud is a hosting service providing online digital maps for web and mobile developers. You can customize the maps, upload or create your own geodata, and publish them online. Then, create a vector layer for importing the GEOJson format airport data. The data was uploaded to Maptiler Cloud. The icon for the dot vector files was selected and the necessary aesthetic corrections were made. In this way, the points in the data were made visible as the selected icon.

---

In HTML projects, pop-ups (or windows that can be opened and closed) can be used for several important purposes. Information Notification: Pop-ups can be used to convey important information to users or to announce certain events. Additional Information or Content: Pop-ups may be used to provide users with more information or display additional content. In our project, pop-ups aim to provide the user with a lot of information such as name, country, phone number, website, and source for the selected airport.


---

## Search Bar

In HTML projects, the "search" menu usually provides the user with an interface to perform a search operation. This menu is designed to help the user find a specific topic or content. The "Search" menu usually contains a text input box. This menu allows the user to quickly access the information they want. Users often navigate through the content of the site or application using this type of search function and can find the topic or page they want. In our project, the search bar was added to find the airports we want to reach, separated by country. Searches can be made using the countries included in the airport data. Another purpose of adding a search bar is to filter the data (on a country basis).

---

## CRUD Section

To enhance the project structure, navigate to the src directory and craft the following components:

* InputForm.js:

This versatile component serves the dual purpose of creating and updating airport information. It provides a dynamic interface that adapts to the specific needs of adding new airports or modifying existing ones.

* AirportList.js:

This component showcases a list of airports and offers options to view, edit, and delete each entry. It provides a comprehensive overview of available airports within the system.

* AirportDetail.js:

This component provides a detailed view of a single airport, presenting a comprehensive overview of its information.

* AirportEdit.js:

This component acts as an interface for editing airport information, allowing users to modify and update the details.
Lastly, integrate these components into the main App.js for seamless interaction and functionality. Ensure proper routing and state management for an optimal user experience.

---

## Workplan
* Background Check for HTML, React, and OpenLayers - Feyza, Beyza, Rümeysa
* An empty website (localhost) was created using react - Feyza
* Selecting base map from Maptiler - Feyza
* Basemap integrated with OpenLayers into a website created - Feyza
* Providing the suitable data for the project - Beyza
* Added airport data to the base map on the website - Feyza
* Changed point data icon - Feyza
* Added pop-up - Feyza, Beyza, Rümeysa
* Added search bar - Beyza
* Create the component of the airport data prepared as crud - Rümeysa

---

Drive link for the project [video]().

