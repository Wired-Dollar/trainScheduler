# trainScheduler

Firebase tag
(<script src="https://www.gstatic.com/firebasejs/6.3.1/firebase.js"></script>)

Moment.js
<script src="moment.js"></script>
<script>
    moment().format();
</script>

<div class = container>"userInput"
var trainName
var destination
var firstTime: require(00:00)
var frequency
</div>

var currentTime = moment();  // current date and time
var arrivalTime = moment.duration({
    seconds: 2,
    minutes: 2,
    hours: 2,
    days: 2,
    weeks: 2,
    months: 2,
    years: 2
}); - currentTime 

Have a card display at the center top of page for the user to see #currentTime

Have user input boxes for vars [trainName, destination, firstTime, frequency] followed below with "add train" button

for.each on.click of button the data will be stored with Firebase for our app

under the userInput card will be another card displaying a live list of all the current trains in the database.

primary id will be destination, as user will be looking for the train that arrives to the location they are to board a function will calc the difference between the currentTime and the arrivalTime and there will be a display stating "next train arriving in ()" to the right of the userInput card displaying this arrival countdown to the user