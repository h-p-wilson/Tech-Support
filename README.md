This is team Tech Support's entry into the Athena Hackathon under the theme "Working From Home".

## The idea
We decided to think outside of the box and provide a solution for companies as well as employees. With a lot of people working from home, we noticed that many offices have been left empty. The supplies and equipment within the offices have been left largely unused as the employees are no longer there to use them. Although some companies do allow their employees to take supplies home, based on the experience of some of our teammates, there is still a surplus of items left in the offices.

That's where renct comes in.

renct is a solution that connects businesses and individuals to not only save money and the environment, but also make working at home much more convenient. Users can browsethe site, fill in the questionaire and then be supplied with a series of companies that are offering the equipment they are looking for. The user can rent the item and take it home with them to make their home office that much more comfortable at a cheaper price. 

We realised that many companies are moving towards flexible working where an employee can work from home on certain days. Because renct can be customised to find items to be rencted on a short term basis, an employee could renct a monitor, for example, on the days they plan to work from home and return it as they wish. 

## The website
Our website features various pages with the most significant one being the questionaire. Here, the user can filter through what they're looking for by entering various details which will aid them in their search for equipment or space:

* **Select the items you require**
* * This so far is a series of tick boxes:
* * * Hardware - laptops, bluetooth mice, bluetooth keyboards, monitors, HDMI cables
* * * Software - Adobe
* * * Furniture - ergonomic chairs, standing desk

* **Select a location**
* * The user chooses a location from an interactive map. 

* **Select a radius**
* * The user can determine how far away they are willing to see results from using a radius from their location. The radius is measured in miles.

* **More details**
* * The user can type in any further details they wish us to know before sending off the information.

## Java interface
In order to demo the interactivity of our site, we decided to use Java to create a text based version of what type of information we would require from users. Various classes
are used to imitate the functionality of the website the main ones being:

* **Reviews**
* * To ensure our users get the best experience using our site and eliminate risk, we decided to employ the use of a review system. Once a user has rencted out an item from a company, they are able to rate their experience with the company and leave reviews. Companies are also capable of doing this. If a user has returned the item they rencted damaged, a company can leave them a bad review or contact us to report them. This ensures our platform remains risk-free and we can offer the best experience to our users.

* **Accounts**
* * As stated previously, renct is intended to connect businesses and individuals. The business will of course be offering the products to renct while the individuals will be doing the rencting. Therefore, these two types of users will have different accounts that can do different things. This has been implemented through the creation of two different Java classes, CustomerAccount and BusinessAccount.
* * These two classes inheret from the parent Account and each have their own seperate attributes.

## Future plans
We believe renct has a lot of potential to make employees and businesses lives easier in a world where working from home is becoming the norm. Although we were not able to add all the features we would have liked in the given time, we thought it would be worth mentioning where we would go with the project:

* **A mobile app**
* * Considering how much shopping is now done from a phone, we believe venturing into the creation of a mobile app would perhaps be more suitable for the individual users. Taking inspiration from the likes of airbnb, we think it would be more convenient for an employee to just pull out there phone and renct something right there and then, making the process much more streamlined
