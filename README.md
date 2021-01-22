# cryptocurrency price alert

## The goal

Create an algorithm to *detect* when the cryptocurrency price exceeds a threshold and *send* a message on skype to alert.

## details on what was done

I use Object-oriented programming (OOP) in Python. 

I select *interval of time* and *time step* to get data on *Zilliqa* cryptocurrency. 

For each data row I look for the passing of a *price threshold*.

if a threshold is exceeded, i send a message to a *recipient* with my *skype account*, else, i do nothing. 

The message contains the *date of the threshold crossing* and *the price of the cryptocurrency*.

The code is *restarted in a loop* after a pause on the previous time interval. 

An *escape key* is defined to exit the loop. 







