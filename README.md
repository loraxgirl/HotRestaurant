# HotRestaurant

* Description: Basic app demonstrating Node and Express with jQuery. Overall purpose is to help schedule reservation requests. Restaurant has just 5 tables available. First five requests get a reservation, every request after that is sent to the waiting list.
* Live Demo: <https://hot-restaurant-fsf.herokuapp.com/>

![Hot Restaurant Image](Images/HotRestaurant.png)

## Notes

* You will NOT need a MySQL Database for this exercise.
* Current app doesn't have admin handling. We'll deal with that at a later time.
* Don't separate the JavaScript from the HTML in the client-side code. (i.e. Don't use external JavaScript. If you do, you will need an additional line of code to configure the express server to know where the JavaScript is).

## Good luck! Don't stress out

* Spend some time trying to build exposure. But don't get overwhelmed. We'll have plenty of time to come back to this.

# Instructions:

* Today you will be building a Node / Express based web applications for handling reservation requests.

* Your application will be made up of two parts: 1) A front-end set of HTML/CSS/JS pages for entering and viewing data and 2) A back-end composed of Node/Express and basic JS for storing, updating, and relaying reservation data.

* Spend the time necessary to map this application out. Consider the concepts we've covered in class so far:

    * Servers
    * Routing
    * APIs
    * AJAX (GET and POST Requests)
    * You should be referencing the code from the previous [Star Wars application](https://uclax.bootcampcontent.com/UCLA-Coding-Boot-Camp/ucla-virt-fsf-pt-03-2020-u-lol/tree/master/13-express/01-Activities/14-FinalStarwarsApp).

* Feel encouraged to use the following application as a reference: http://hot-restaurant.herokuapp.com/

* Note: We know this is a hard activity. We know you aren't yet comfortable with Node or Express. But push yourself. The best way to learn is to push through the discomfort and BUILD! Ask for help when you need it. We're here to help you through the process.

* Bonus:

    * If by some miracle you finish early, feel encouraged to work on any one of these additional tasks to take your application to the next level.

        * Add code to your server so that it "counts" every time a person visits any of the pages. Display a running count on the website.

        * Add buttons for "checking off" individuals from the reservation list. Once this happens, the next person on the waitlist should be addd to the main reservation list.

        * Add a button for sending emails to individuals on the wait-list letting them know they have a table ready. You will need to use node-mailer or a similar npm package to make this work. (A hard task, but very cool).

        * Add a button for sending text messages to individuals on the wait-list letting them know they have a table ready. You will need to use the Twilio library to make this work. (A hard task, but very cool).


* Additionally, you may want to reference the diagram below at some point during your coding. It may help you visualize the overall application you are building.
![Hot Restaurant Image](Images/Diagram.png)