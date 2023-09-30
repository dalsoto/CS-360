# CS-360

The purpse for the application of the Event Tracker was to be able to have a list of 
the events for previous and future events into a database.  The user should be able to 
add and delete from this database.  Being able to log into your own account is also required.  The screens of this app included the log in screen were you can be directed to a sign up screen if you dont have an account yet.  The home screen that has the list of all the future events.  The add and update screens as well.  I did a lot of researching for this app as in looking into similar apps and into what works best.

Since Android was very new to me, I had to do a lot of research on how to properly code functions, such as SQLite databases, alert dialogs, and lists. This taught me how to look for solutions to problems. Research is very important in system development, especially if the developer is asked to build something they have no prior knowledge of that subject.

I ran my application after developing every feature to see if everything worked properly. Also, I used breakpoints while I debugged the system to figure out issues when my application wasn't working properly. For example, the SMS notification was not working properly, even though SMS permission was accepted. With the help of breakpoints, I was able to figure out that the user phone number input was null and I forgot to add the phone number to the database bundle.
