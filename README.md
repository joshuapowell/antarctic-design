# Antarctica
A sandbox to design a React/Redux application, with a Django/PostgreSQL API, and basic DevOps.

## Overview
How to go from nothing to a design system for our Antarctica application.

We begin by identifying user needs and data management tasks. Next, we break down the individual user interface components that will be used in each data management task to help us indentify a common visual language to use across the system.

#### User Needs 
- Identify research stations
  - by country
  - by status
- Identify environmental data about specific research stations

#### User Data Management Tasks
- Import new list of research stations
- Add a new research station
- Edit an existing research station
- Remote a research station
- View a research station detail page
- View a list of research stations
- Filter a list of research stations
- View all research stations on a map
- View a details about a research station by clicking on a map pin
- Download a GeoJSON file of all research stations (excluding environmental indicators)
- Download a CSV file of all research stations
- Download a Shapefile of all research stations
- Import a list of research station environmental indicators
- Add a new measurement
- Edit an existing measurement
- Remove a measurement
- View multiple measurements on a time series chart
- View a table of measurements
- View sources of all data on site

### Design System
Based on user needs and user tasks listed above the following user interface components will be required in our design system.

- Color usage
- Typographic usage
- Form component
- Header/Footer component
- Primary navigation
- Secondary navigation
- Card component
- List component
- Table component
- Map component
- Chart component