# Daily-Planner

https://markyounan11.github.io/Daily-Planner/

Description:

This is a daily planner application that allows the user to input events happening each hour within their 9-5 work day. Once user inputs the specific event, they can click save the corresponding save button and the event they inputted will be saved to local storage. This will keep the event they inputted appended to the page even after refresh, so they can refer back to the page as they find fit.

The application utilizes live local time meaning the hours that have already happened are grayed out and the current hour is highlighted in red, while the rest of the future hours are highlighted in green. These color schemes update in real-time as you go throughout the day.

Technologies:

The languages used to create this app are HTML, JavaScript, and CSS. Frameworks used were Bootstrap and Font Awesome. To display/manipulate time, I used moment.js.

Challenges:

This application was challenging in figuring out how to dynamically create new rows and append while incorporating the utilization of local storage. Essentially, all the logic to manipulate the time and colors is within one very large function.