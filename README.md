# Take Home Assignment - Senior Full Stack 
### Interface + API application (Insight Card)
---
**IMPORTANT** : we will consider exclusively the quality of your project (technology and product-wise) to evaluate your work. We've added a project structure in this repository (a buildwith react, reflux, typescript, wepback, babel config etc) to save you time. Feel free to use it.

Quantive Signals monitors your KPIs and intelligently collects your data , identify anomalies, Identify factors that create unexpected changes , generates alerts and insights of when, what, and why something happens.

You will build a piece of our insights feature by creating the insight card screen.
### Development Instructions
---
**Evaluation**
Be aware that Origin will mainly take into consideration the following evaluation criteria:
- How close your page is to the mockups, both on mobile & desktop;
- How clean and organized your code is. We are looking for clear separation of back-end and front-end;
- If you implemented the business rules correctly.
- How good your automated tests are, i.e.: qualitative over quantitative. Feel free to choose between jest or testing library.
- You are free to use any javascript chart library.

You can use third-party libraries in case you want to.

### Assets
---
**Desktop view**
image will be here...
**Mobile view**
image will be here...

### What you have to make
---
**signup screen**
- create a signup screen in the [host]/auth/register page.
- On Submit, create an entry of the registered user in the DB (e.g mongodb) of your choice.

**login screen**
- create a login screen in the [host]/auth/login page.
- On Submit, validate the user and as soon as user gets logged in, user will redirect to [host]/organizations/quantive page where you will show your insight card screen.

**insight card**
insight card will have the following components.
- insight card heading with the source logo and breadcumb like structure i.e source_name/stream_name/kpi_name along with that, the severity i.e [high, medium, low].
- insight card heading will also have the watchers components. suppose user1 was the owner of an insight and user2 (another logged in user) clicked that insight card, user2 will be added as the watcher for that insight and will be visible in the watchers component.
- insight card have the table with the top-drivers (data is in notion). Show first 2 top drivers.
- insight card also have the line graph. You can use any javascript chart library to create it, (data is in notion)
- insight card have the save button, On submit save the insight for that user. 
- create a filter based on siverity and saved insights.

### Tech
---
**required tech for this assignment**
- frontend -> React.js
- backend -> Node.js
- database -> mongodb (optional) free to use any db
- chart librabry -> Echarts (optional) free to use any charting library
- testing -> Jest (optional) free to use any testing library
- state management -> Reflux
