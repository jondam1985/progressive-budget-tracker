# progressive-budget-tracker

# Description

This is a full stack progressive web app that allows user keep track of their budget and saves transactions in a NoSQL database. This was developed for my Full Stack Web Development bootcamp.

<iframe src="https://drive.google.com/file/d/1Oljv8ozHoiUon0P2eD0A9EGwu-bQ0l33/preview" width="640" height="480"></iframe>



# Content

1. [Installation](#Installation)
2. [Usage](#Usage)
3. [Credits](#Credits)
4. [License](#License)



# Installation

[Clone this repository]( https://github.com/jondam1985/fitness-tracker ) and run `npm install`.

Make sure you have `mongoDB` installed in your machine.

To run locally execute `npm start` and access via `localhost:3000`.

To visit the production version go to https://mo-money-less-money.herokuapp.com.



# Usage

To add a new transaction write a name in the NAME OF TRANSACTION field and a quantity in the TRANSACTION AMOUNT field. Then click on ADD FUNDS if the transaction is an income, and click on SUBSTRACT FUNDS if the transaction is an expense.



# Credits

### Author

This web app was developed by [Damian Ruiz](https:www.github.com/jondam1985) as a project for the [UofT Full Stack Web Development bootcamp]( https://bootcamp.learn.utoronto.ca/ ).



### Dependencies

- Server developed using [Express]( https://www.npmjs.com/package/express )
- MongoDB schema created with [Mongoose]( https://www.npmjs.com/package/mongoose )
- HTTP requests logged with [Morgan]( https://www.npmjs.com/package/morgan )
- Request compression middleware [Compression]( https://www.npmjs.com/package/compression )
- Browser synchronization during development done with [lite-server]( https://www.npmjs.com/package/lite-server )
- Chart created with [chart.js]( https://www.chartjs.org/ )



# License

This project is licensed under the MIT standard license. [Click here for more details about the MIT License]( https://opensource.org/licenses/MIT ).