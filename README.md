# AKAN-names

[Check it out](https://kaphie.github.io/AKAN-names/)

### Author:

KAFRIKA BENITAH

## Description
This is a web application that takes a ``user's birthday``,calculates the ``day of the week`` they were born
and the depending on there gender out puts there ``akan name``.

Akan names are derived from Ghanian culture. Frequently in Ghana, children are given their 
first name as a ``day name`` which corresponds to the day in the week they were born. Here are Ghanian day names.

Male
Sunday: Kwasi

Monday: Kwadwo

Tuesday: Kwabena

Wednesday: Kwaku

Thursday:  Yaw

Friday: Kofi

Saturday: Kwame

Female
Sunday: Akosua

Monday: Adwoa

Tuesday: Abenaa

Wednesday: Akua

Thursday:  Yaa

Friday: Afua

Saturday: Ama

Most people do know when their birthdays are, but some might not know what day ofthe week they were born. 
Luckily for us, there are ways to calculate the day of the week from a specific date. The following is one of
the many methods that exist for that;

## BDD

Day of the week (d) = ( ( (CC/4) -2*CC-1) + ((5*YY/4) ) + ((26*(MM+1)/10)) + DD ) mod 7

  |Inputs |  Description |
| :---        |              ---:|
|CC        |is the century digits, ``e.g 1989 has CC = 19``|
|YY       |is the year digits, ``e.g 1989 has YY = 89``|
|MM        |is the month of the year,``e.g 5th month`` |
|DD       |is the day of the month ``e.g 24th day`` |
|mod    |is the modulous function, ``%``    |

#### USER STORY
 As a user, I would like to;

See a  small description of what the application does on the landing page.
Enter my birthday through a form 
Choose what gender I am.
Click the submit button to see what my Akan name would be

## Screenshot.
<image src="https://github.com/kaphie/AKAN-names/blob/master/image/Screenshot%20from%202020-02-15%2018-15-02.png" width="1000">

 

### Setup Instructions:
> Fill in all the fields and tap *submit* button to find out what your akan name is.

## Technologies Used:

* html
* css
* bootstrap
* javascript
* markdown

## Known Bugs

There was a bug that returned the ``akan name`` as undefined which has still given me hard time to figure out.

## License
> MIT License &copy 2020 Kaphie

## Collaborate
To collaborate, reach me on [Email](bkafrika144@gmail.com)





