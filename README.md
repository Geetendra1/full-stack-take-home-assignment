# Take Home Assignment - Senior Full Stack 
### Interface + API application (Insight Card)
---
**IMPORTANT** : we will consider exclusively the quality of your project (technology and product-wise) to evaluate your work. We've added a project structure in this repository (a buildwith react, reflux, typescript, wepback, babel config etc) to save you time. Feel free to use it.The app will also have its own separate login mechanism based on a username and password. Go through the details clearly. You have        **7 days** to submit the assigned task. We of course want you to solve the problem, but are equally interested to see how you solve it - the quality of your approach & code!
In case of any questions, send a mail to nidhi@gtmhub.com

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
![alt text](https://cliff-uploads.s3.amazonaws.com/image+(2).png
"Logo Title Text 1")




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

### Delivery Instructions
---
Follow the below instructions for your submission :
- Please send your submission to this form:[link](https://airtable.com/shrqTib6f8G15e0UE)
- Reply to the email with the assignment/link/attachments/ submission.
- Create a private repository on Github and add the following accounts as collaborators :
    1. aayush.jain@greendeck.co
    2. geetendra@greendeck.co
    3. rohit.sharma@greendeck.co
- Please ensure that your repository has a ```README.md``` which lists the exact steps required to run your application.
- Send an email to ```careers@greendeck.co``` with the subject "Full-stack assignment submission" (do not use any other subject) and mention the following details in your email:
    1. A link to the application's GitHub repository (make sure you've added the collaborators mentioned previously).
    2. The hosted URL of your web-app (if hosted on a platform such as Heroku).


### Usage
---
This project requires the latest LTS version of NodeJS and you may need to install the yarn as global dependency

```
npm install -g yarn
```
After you have cloned this repo and install the yarn, install the dependencies with:
```
yarn install
```
You can then start the application running:
```
yarn start
```
That's it. Just Access http://localhost:6001 in your browser.

**Again, please make sure your repository on GitHub is private.**


We hope you have fun with the assignment! In case of any questions or queries, feel free to shoot us an email at careers@greendeck.co. We are expecting a solution submission within seven days. While we're interested in the complete implementation of the task, feel free to submit your solution even if you feel if it's not up to the mark; we're as interested in your method of solving the problem as we're interested in the end result itself.

Good luck!
