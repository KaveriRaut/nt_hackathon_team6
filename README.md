# Project Title : Currency_Exchange Project

# About the Project: 📚
In this Project we have created a dashboard which we allow users to analyze the exchange rates between two currencies over a period of time. Users have option to select start and end date for displaying currency chart. Data is printed and the form of chart using chart.js technology. Input will be
currency exchange rate dataset between a currency pair and will be provided in a file format.

## Frontend
 - The frontend of the web application has been created using React.js. React makes it painless to create interactive UIs, and effectively updates and renders the correct components as the data changes. 
 - The front end has form inputs for the currencies for which the currency exchange rate needs to be displayed. Inputs are also taken for the starting and ending date (in other words, the first x-coordinate and last x-coordinate in a line graph). 
 - The csv file from which the data is to be imported can also be selected by the user, alongside the type of view they want in the graph - Day, Quarterly, Month and Year. 

## Backend
- For the backend ,we convert given CSV to JSON format  using  reactJS.
- Then we filter data in JSON format according to date and currency using in-build function.
-  With the help of chartJS package we plot graph for user entered values.
(Due to the lack  of time,we just convert data of only 2month(1Jan 2012 to 29feb 2012)) .that is why it is showing an graph for range of date between 1jan 2012 to 29feb 2012.Later we can definitely convert entire data into json format.So that  it will work for any date.

##Technologies Used: ⚛️
React js, Chart.js

## Setup / Installation: 💻
Setting React App
  -npx create-react-app my-app
  -cd my-app
  -npm start

## Screenshots: 📷
![1](https://user-images.githubusercontent.com/97447480/205901106-26f23004-73af-4f71-8978-79fbcf66f9c8.jpg)

## Output
![2](https://user-images.githubusercontent.com/97447480/205901144-424e0575-36cd-406e-ac5d-1c9e40508377.jpg)
