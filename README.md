# SystemIntegration-MOM-assignment1
Solution: (car rental chosen)
There exists altervative solutions to solve this problem using different kinds of message exchanges, 
but for this campaign, topic exchange is used.  

Agenda:
The main idea is to broadcast the campaign "Dreams come true this autumn" offering cheap services, 
and get confirmation from the potential customers (those who do not write "pass").
A TravelAgency script is started offering the campaign and waits for customers to   

Binding key is "Dreams come true this autumn.book"

Procedure:

Open a terminal and type:
1. python .\TravelAgency.py "Dreams come true this autumn.book" "Rent a car for half price the whole season"

Open a second terminal and type:
2. python .\customers.py "Dreams come true this autumn.book" "Rent a car for half price the whole season"

Open a third terminal and type:
3. python .\customers.py "Dreams come true this autumn.pass" "Rent a car for half price the whole season"

Switch back to terminal 1 and verify that only listed is the ones with binding key book, and pass is not listed.
