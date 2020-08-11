# CshMarathon_Sprint13
 C# Marathon Sprint13
Sprint 13. Tasks
All the views are based only on the Razor syntax.
1.	Change Index view:

1)	Change the title of tab;
2)	Add navy bar “Sprint Tasks” that redirect to page “Sprint Tasks”;
3)	‘Our project’ is a link to your project on Git.

2.	View ‘Sprint Tasks’:
 
The page contains navigation bars  that redirect the user to the appropriate view-pages.

3.	View ‘Greetings’:
 
1)	Messages are placed as variables;
2)	Use DateTime methods;
3)	Use branching to send the greeting (evening or morning).

4.	View ‘ProductInfo’
 
1)	Create the class Product with properties: Name (string), Price (double)
2)	Use this class to create the list of products just within the view.
3)	Use loop to output the information on the page.

5.	View ‘SuperMarkets’
 
View page receives the list of supermarkets via ViewBag and output it with their quantity.

6.	View ‘ShoppingList’
 
View page receives the model dictionary from controller. Dictionary contains name of product (key), quantity (value).
View contains partial view ‘TimeToBuy’

7.	Partial view ‘TimeToBuy’ uses @inject.
You have to:
1)	Create the folder Services;
2)	define interface ITimeService with method GetTimeForTomorrow();
3)	the class SimpleTimeService, that implement interface ITimeService. The method GetTimeForTomorrow() have to return the time for shopping just in a day;
4)	inject dependencies into view to output the time of shopping for tomorrow.

8.	View ‘ShoppingCart’
 
The page contains controls that you have to define using html-helpers:
1)	Input boxes;
2)	DropDown box that receives and contains the list of supermarkets;
3)	RadioButtons with values according to the today-date. User can choose date to ship order;
4)	ListBox that receives the keys of dictionary (use ShoppingList);
5)	‘submit’ input.
You should consider both (HttpPost and HttpGet) controller methods for this view.
As the result of submit user might receive the message:
 

