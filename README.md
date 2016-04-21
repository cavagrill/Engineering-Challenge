# Background
This exercise is meant as a way to produce code for the Cava Grill team to review. If the candidate has something that is
comparable, open source, they may choose to send that along rather than completing the exercise below. As a disclaimer, all the
data in this exercise is fake, and does not represent the full picture of Cava Grill operations.

#Task
At Cava, restaurant managers need the ability to inventory our products for their store. To do this, we have restaurant logins,
product lists and product units. A manager takes a count of each item in the list, then records them into the app.
Hypothetically, our app is pretty old and needs to be updated into Elixir and React. A manager should be able to log in using
his/her restaurant log in, and inventory each product. Our Supply Chain team will then take a look at the data and run some
analysis on the daily inventory that a restaurant has reported to get an idea of usage. 

Note: This is a somewhat open ended task, no wireframes have been provided. Please use Elixir and React, but feel free to make
any decisions on your own related to incorporating other technologies or designing the simple user interface as you see fit.
However, for any major design or tech decisions you make, please justify them in the README.md of the github repo you submit.

Note 2: This is a hypothetical scenario, the code you produce for this exercise will never be used in any of our inventory tools
in restaurants.

#Requirements 
1. Each restaurant, in the provided stores.txt must have a unique identifier and login, that can be authenticated. How you
implement this is up to you (but please hash the passwords :) )
2. Ability to write to a database the daily inventory count for each item at a restaurant, in the provided items list.
3. Simple user Interface for recording inventory counts.
4. Ability to view previous inventory counts sorted by date and item.
5. BONUS: Currently, managers import inventory as standard units, such as 1 package. You are given a list of units in ounces, mL,
etc for each item. Have the app convert these units for displaying in Requirement 4.

