Team Members:
Victoria Lawton
Sriya Kurrapath

**Question 1:** What are the denominations of the US coins from the green, blue and orange
distributions? Can you think why the coins from the same denomination might show variation in
weight although they are specified to be of the same weight? If your vending machine had a
weight sensor, how would you use the weight of a coin that was just inserted to find the
denomination?

The green distribution is from pennies. The blue distribution is from nickels. The orange distribution is from dollar coins. Coins from the same denomination might show variation in weight because of small differences in manufacturing and degradation of the material over time. For a vending machine with a weight sensor, you could find the denomination by checking to see if it's in the weight range of a given coin (i.e. for a nickel, check to see if it's between 4-6 g).

**Question 2:** We can shine light on the coin and measure the reflected amount of light which
should be proportional (directly or in some non-linear way) to the size/area of the coin. Can you
guess which sensor on the Grove Pi Kit can be used for this purpose?

The photoresistor measures differences in light intensity and could be used for this purpose.

**Question 3:** Which of the following datasets are linearly separable? Justify your answer.

Linearly separable datasets refer to datasets where the data points corresponding to the same class can be separated by a straight line from data points corresponding to a different class. This includes datasets A, C, and D. 

**Question 4:** Sometimes we need more than a simple hyperplane to separate the datasets of the
two classes. What are some other simple geometric entities other than a simple plane/line that
can be used to separate some of the data points that were not linearly separable?

Some other simple geometric entities that can be used include circles, a pair of lines, parabolas, ellipses, and hyperbolas.

**Question 5:** For example shown in the figure, what is approximately the output of the neuron?

Input 1: value = 2, weight = 1
Input 2: value = 1, weight = -2
Input 3: value = 2, weight = 3
bias of the neuron = -2

z = (2 * 1) + (1 * -2) + (2 * 3) -2 = 4

y = σ(4) = 1/(1+e^-4) = 0.982
