# Covid_vaccination_portal
You are provided with vaccination dataset named vaccine_data. The dataset 
contains following fields:
Userid ,Name , 1st dose status ,1st dose date ,2nd dose status, 2nd dose date
#Your Task
Create a portal which shows vaccination status of registered people (who’s id is 
present in the dataset) using userid.
1. If the user has taken both the doses then it should show, 
“Congratulations! You are fully vaccinated”.
2. If the user has not taken any dose then it should show, “Please take your 
first dose at earliest”.
3. If the user has taken 1st dose but not taken the 2nd dose and if the 
difference between 1st dose date and today’s date is greater than 90 days 
then it should show, “You have taken your first dose on <date of first 
dose>, please take your 2nd dose at earliest.
4. If the user has taken 1st dose but not taken the 2nd dose and if the 
difference between 1st dose and today’s date is not greater than 90 days 
then it should show, “You have taken your first dose on <date of first 
dose>, please take your 2nd dose on or after <next dose date>.”
Note: The next dose will be 90 days after the first dose date
Important Note:
-Before every message, you must show greet the user. Example
o Hi Chandler, Congratulations you are fully vaccinated.
-The date format must be DD/MM/YYY
