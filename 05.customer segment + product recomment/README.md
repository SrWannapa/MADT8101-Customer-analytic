## Customer segment + Product Recomment
from the supermarket data set as the previod Toppic
the dataset infomation as the image below

![image](https://github.com/SrWannapa/MADT8101-Customer-analytic/blob/main/05.customer%20segment%20%2B%20product%20recomment/Data_info.jpg)

BEFORE WE DO ANALYSIS WE HAVE TO CLEAN THE DATA AS NaN SO THE RECORD WILL BE 433142 ROWS FROM 578982 ROWS

## Segment by the customer shoping time 
 we focus in the passenger flow during each period of a day show in the distribution. the most customer come to supermarket around 14:00 and 21:00

![image](https://github.com/SrWannapa/MADT8101-Customer-analytic/blob/main/05.customer%20segment%20%2B%20product%20recomment/the%20passenger%20flow.png)

We go deep to quatity they bought the product at 14:00 is the time is the smallest quanity and the biggest order in the early morning because is the time they are buy the goods for cook breakfast or some mother come to shopping after they sent their childen to school then going back home.

![image](https://github.com/SrWannapa/MADT8101-Customer-analytic/blob/main/05.customer%20segment%20%2B%20product%20recomment/The%20relationship%20between%20average%20quantity%20and%20hour.png)

and the last one is the relationship between basket size and hour

![image](https://github.com/SrWannapa/MADT8101-Customer-analytic/blob/main/05.customer%20segment%20%2B%20product%20recomment/The%20relationship%20between%20basket%20size%20and%20hour.jpg)

## Segment by the price

customers' price sensitivity,conclude the average consumption level

![image](https://github.com/SrWannapa/MADT8101-Customer-analytic/blob/main/05.customer%20segment%20%2B%20product%20recomment/The%20relationship%20between%20price%20sensitivity%20and%20spend.png)

##  Segment by Lifestage
The most customer price sensitivity is in the MM and the customer lifestage is OT.

![image](https://github.com/SrWannapa/MADT8101-Customer-analytic/blob/main/05.customer%20segment%20%2B%20product%20recomment/The%20customer%20price%20sensitive%20with%20the%20number%20Customer%20Lifestage.jpg)

young family are the largest consumer groups(except OT).

![image](https://github.com/SrWannapa/MADT8101-Customer-analytic/blob/main/05.customer%20segment%20%2B%20product%20recomment/Composition%20if%20the%20customers%20proce%20sensitiviy.png)

## Behavior in each month
in the 1st yesr trend is be growthing up. It seem the supermarket just grand opend so they had many promotion to promote the supermarket. then stable in the 2nd year. and the Nov to Dev the costomer will come to buy the goods for Christmas gift and new year gift.

![image](https://github.com/SrWannapa/MADT8101-Customer-analytic/blob/main/05.customer%20segment%20%2B%20product%20recomment/Movement%20of%20customer%20visit%20times.jpg)

# Product recommentation
We make a pivot table to summary which product was bought by each customer

![image](https://github.com/SrWannapa/MADT8101-Customer-analytic/blob/main/05.customer%20segment%20%2B%20product%20recomment/product%20was%20bought%20by%20each%20customer.jpg)

After we are creating the customer-item martrix we use the collaborative filtering to see the relation product with customer by cosine similarity

![image](https://github.com/SrWannapa/MADT8101-Customer-analytic/blob/main/05.customer%20segment%20%2B%20product%20recomment/User%20based%20collaborative%20filtering.jpg)

then we look at the top 10 of customer to making recommendation
![image](https://github.com/SrWannapa/MADT8101-Customer-analytic/blob/main/05.customer%20segment%20%2B%20product%20recomment/top%2010%20customer.jpg)

and we pick CUST0000000181 to do which product we should recommend in group A and B
![image](https://github.com/SrWannapa/MADT8101-Customer-analytic/blob/main/05.customer%20segment%20%2B%20product%20recomment/Item%20A.jpg)
![image](https://github.com/SrWannapa/MADT8101-Customer-analytic/blob/main/05.customer%20segment%20%2B%20product%20recomment/Item%20B.jpg)





