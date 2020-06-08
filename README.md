
# Linear Regression Analysis

Ecommerce company that sells clothing online but they also have in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want.

The company is trying to decide whether to focus their efforts on their mobile app experience or their website.

Customer data (it's fake, don't worry I didn't give you real credit card numbers or emails).

## Data


* Avg. Session Length: Average session of in-store style advice sessions.
* Time on App: Average time spent on App in minutes
* Time on Website: Average time spent on Website in minutes
* Length of Membership: How many years the customer has been a member. 

![pairplot](https://user-images.githubusercontent.com/64975026/84069972-00faa600-a991-11ea-852d-39851af4761a.png)


## Conclusion

This model explained ~ 98% of variance
![model](https://user-images.githubusercontent.com/64975026/84070076-2982a000-a991-11ea-99d1-f7cea5836dfa.png)

Interpreting the coefficients:

- Holding all other features fixed, a 1 unit increase in **Avg. Session Length** is associated with an **increase of 25.98 total dollars spent**.
- Holding all other features fixed, a 1 unit increase in **Time on App** is associated with an **increase of 38.59 total dollars spent**.
- Holding all other features fixed, a 1 unit increase in **Time on Website** is associated with an **increase of 0.19 total dollars spent**.
- Holding all other features fixed, a 1 unit increase in **Length of Membership** is associated with an **increase of 61.27 total dollars spent**.
