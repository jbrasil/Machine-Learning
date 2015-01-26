A/B Testing.
-----------------------------------------------------
In marketing and business intelligence, A/B testing is jargon for a randomized experiment with two variants, A and B, which are the control and treatment in the controlled experiment. Instead of a statiscal test, where one can only get if there is a significante difference between the two branches of the test, here is going to be explained another statistical approach to help you decide what thest to choose when the experiment is completed.

There are several variables that can be tested on a experimente like this, every variable follow a probability distribution that needs to be derived. After having the probability density function one can extract value information regarding the behavior of the variable to test, such as:
- Expected value
- Probability that the variante is going to reach the aim value for that test

Model for exit rate(Bouce) and conversion rate.
------------------------------------------------
Exit rate and conversion rate can be moduled in the same way. One can take a Binomial approach to modul both Exit's and Conversions on a e-commerce platform.
Assuming that we are using a Binomial distribution it make sense to have as conjugated prior a beta distribution. After some calculations, we define exit rate and conversion rate as the follow:
$$
\Theta(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$
