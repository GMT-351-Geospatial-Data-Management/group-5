![alt text](https://www.freelogovectors.net/wp-content/uploads/2020/07/hacettepe-universitesi-logo-768x178.png)

# GMT351- Geospatial Data Management Group-5 Final Project Report
---
* Beyza ÖZKAN - 21833369
* Rümeysa Nur KELEŞ - 21833283
* Feyza KARAKELLE
---
The purpose of the project we created, is to display the airport points correctly on the basemap on the created website, to prepare pop-ups that provide information about the selected airports, to filter the selected data according to countries, and to enable the user to create read update delete applications. HTML, React, JavaScript, Openlayer were used in the project.


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
* Background Check for HTML, React and Openlayers - Feyza, Beyza, Rümeysa
* An empty website (localhost) was created using react - Feyza
* Selecting basemap from Maptiler - Feyza
* Basemap integrated with openlayers into website created - Feyza
* Providing the suitable data for the project - Beyza
* Added airport data to the basemap on the website - Feyza
* Changed point data icon - Feyza
* Added pop-up - Feyza, Beyza, Rümeysa
* Added search bar - Beyza
* Create the component of the airport data prepared as crud - Rümeysa



