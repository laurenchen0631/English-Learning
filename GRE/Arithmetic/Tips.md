## General
- **To get a squared number which ends with 5, we slice 5 from the number and multiple it with its increment with 1, and postfix the result with 25.**
	- 35^2 = (3 * 4), 25 = 1225
	- 75 * 75 = (7 * 8), 25 = 5625
	- 115 * 115 = (11 * 12), 25 = 13225
- **To get (n+1)^2, if we know n^2, we add n and (n+1) to n^2, and then the result will be (n+1)^2**
	- n^2 + n + n + 1 = (n+1)^2
	- 41^2 = 40^2 + 40 + 41 = 1681
	- 69^2 = 70^2 - 70 - 69 = 4761
	- 84^2 = 85^2 - 85 - 84 = 7225 - 169 = 7056

## Number
- Real Number: any number on the number line including fraction/decimal, which can be positive, negative, or zero.
- Zero (0) is neither positive nor negative.
- Integer: All positive and negative **whole number**. {..., -3, -2, -1, 0, 1, 2, 3, ...}
- sum: the result of addition
- difference: the result of subtraction
- product: the result of multiplication
- quotient: the result of division 
- dividend: 20 / 3, and 20 is the dividend
- divisor: 20 / 3 and 3 is divisor
- numerator: a/b, a is numerator
- denominator: a/b, b is denominator
- absolute value: the distance of a number from the origin. |0| = 0
- factor, divisor, divisible: If A, B, C are all integers, A*B = C
	- A and B is the factor of C.
	- A and B is the divisor of C.
	- C is divisible by A or B.
- multiple: if x is a multiple of y, then y is a factor of x.
	- if two multiples of a number is added together, the sum is also the multiple.
	- if two multiples of a number are subtracted, the difference is also the multiple.
	- the product of two multiples of a number is also the multiple.
- prime: a number that has only two factor: 1 and itself.
	- 1 is not a prime number.
	- 2 is the only even prime number.
	- prime < 20: 2, 3, 5, 7, 11, 13, 17, 19
	- 20 < prime < 60: 23, 29, 31, 37, 41, 43, 47, 54, 59
	- prime > 100: test whether the number is divisible by prime numbers less than 10 (2, 3, 5, 7).
	- Prime Factorization
		- A number must be a prime number or the product of prime numbers.
- GCF (Greatest Common Factor): **Use prime factorization to find GCF**
	- GCF of 360 and 800 is 2^3 * 5 = 40
		- 360 = 2^3 * 3^2 * 5
		- 800 = 2*5 * 5^2
- LCM (Least Common Multiple), LDC (Least Common Denominator): **Use GCF to find LCM**
	- The LCM of 24 and 32 is 8 * 3 * 4 = 96
		- 24 = 2^3 * 3
		- 32 = 2^5
		- GCF = 8, and then rewrite the numbers in the form of GCF
		- 24 = 8 * 3
		- 32 = 8 * 4
		- The LCM is the product of the three factors.
	- If G is GCF, A = G * M and B = G * N, the LCM of A and B is G * M * N
	- **LCM = (A*B) / GCF**
	- If A is a factor of B, the LCM must be B
	- If GCF of A and B is 1, the LCM must be A * B
- Consecutive integers: {1,2,3,..}, {70,71,72}
	- If there are n consecutive integers, there must contain a number that is divisible by n
	- If n is odd, the sum of n consecutive integers must be divisible by n: ... n-2, n-1, n, n+1, n+2 ...

## Even and Odds Integer
- 0 is an even number
- E + E = E and E - E = E
- **O + O = E and O - O = E**
- E + O = O and E - O = O
- E * E = E
- O * O = O
- **E * O = E**
- Division of evens and odds has general rule.
	- E/E = E or O or decimal
	- O/O = O or decimal
	- O/E = x or decimal

## Fraction
- if a > b and a&b are numerator, then (a/c) > (b/c)
- if p > q and p&q > 0 and are denominator. then (s/p) < (s/q)
- Cross multiplication: a/b = c/d --> ad = bc
- **Comparison using cross multiplication**
	- (7/11) ? (5/8) --> 56 ? 55 --> (7/11) > (5/8)
	- (9/20) ? (4/9) --> 81 > 80 --> (9/20) > (4/9)
- **If we add a number p to the numerator and a number q to the denominator, the result will get close to p/q.**
	- For the number that is less than p/q, the result become greater.
	- For the number that is greater than p/q, the result become smaller.

## Percent
- Increase: X is 30% greater than Y, Y increased by 30%
- Decrease: X is 30% less than Y, Y decreased by 30%
- Percent Difference: new/old
	- 60 -> 102, p = 102/60 - 1 = 17/10 - 1 = 1.7 - 1 
	- 250 --> 200, p = 200/250 = 0.8
- 200 -> 800
	- 800 is 400% of 200.
	- 800 is 300% greater than 200.
- Simple Compound
	- Bob deposit $1000 in an account that yields 5% simple interest annually.
		- 1 yr: $1000 + $50 = $1050
		- 2 yr: $1050 + $50 = $1100
		- 3 yr: $1100 + $50 = $1150
		- n yr: $1000 + (1000 * 0.05) * n
- Compound interest
	- Bob deposit $1000 in an account that yields 5% interest compounding annually.
		- 1 yr: $1000 * 1.05 = $1050
		- 2 yr: $1050 * 1.05 = $1102.5 
		- 3 yr: $1102.5 * 1.05 = $1157.625
		- n yr: $1000 * 1.05^n
	- If the question compound quarterly, monthly, or daily, we need n, which is the number of times that compounding period would occur in a year.
		- quarterly: n = 4
		- monthly: n = 12
		- daily: n = 365
	- If the bank pays 5% annual interest, compounding quarterly, the bank pays 1.25% quarter compounding interest.
	- **Use simple compound to approximate the compound interest** 

## Divisibility
- **How to find all factor of a large number?**
	- 2400 = 24 * 100 = 8 * 3 * 25 * 4 = 2^5 * 3 * 5^2, the number of factor = (5+1) * (1+1) * (2+1) = 6 * 2 * 3 = 36
	- How to find all *odd* factor: remove factor 2 from permutation. ~~(5+1) *~~ (1+1) * (2+1) = 2 * 3 = 6
	- How to find all *even* factor: all factor - odd factor. 36 - 6 = 30
- Advance:
	- prime factorization of 1599 (a^2 - b^2 = (a+b)(a-b))
		- 1599 = 1600 - 1 = 40^2 - 1 = (40 + 1)(40 - 1) = 41 * 3 * 13
	- 0.999951 / 0.993 = (1 - 0.000049) / (1 - 0.007) = (1+0.007)(1-0.007) / (1 - 0.007) = 1.007
- Divisibility Rule
	- Divisibility Rule for 2: all even numbers are divisible by 2.
	- Divisibility Rule for 3: if the sum of each digits is divisible by 3, the number is divisible by 3.
		- 135, 1 + 3 + 5 = 9, thus 3 is the factor of 135.
		- 102334155, 1 + 0 + 2 + 3 + 3 + 4 + 1 + 5 + 5 = 24, thus 102334155 is divisible by 3.
	- Divisibility Rule for 4: if the last two digit is divisible by 4, the number is divisible by 4.
	- Divisibility Rule for 5: numbers that ends with 0 or 5.
	- Divisibility Rule for 5: the number must be divisible by 2 and 3.
	- Divisibility Rule for 9 if the sum of each digits is divisible by 9, the number is divisible by 9.
		- 1296, 1 + 2 + 9 + 6 = 18,  thus 1296 is divisible by 9.

## Algebra
- Ax^2 - B^2 = (Ax+B)(Ax-B)
- (a+b)^2 = a^2 + 2ab + b^2
- Absolute Value Equation
	- |Ax+B| = Cx + D
	- Ax + B = Cx + D or Ax+b = -Cx - D
	- solve x and take the result back to the original equation to **check if the results works.**
	- Example. |2x+5| = x+1, 2x+5 = (x+1) or (-x-1), x = -4 (|2*-4 + 5| !== -4 + 1) does not work and x = -2 (|2*-2 + 5| !== -2 +1) also doesn't work.

## Comparison
- A < B: A is **less** than B
- A > B: A is **greater** than B
- A <= B: A is less than or equal to B
- A >= B: A is greater than or equal to B
- If we multiply or divide by a **negative** number, **it reverse the order of inequality.**
	- -x > 3 --> x < -3
	- 3 < 7 --> -3 > -7
- if a > b and c > d
	- [O] a+c > b+d
	- [X] a-c > b-d (15 > 8, 10 > 2 --> 15 - 10 > 8 - 2)
	- [O] a-d > b-c (20>15, 12>10 --> 20 - 10 > 15 - 12)
	- [X] ac > bd (true iff abcd are all positive)

## Word Problems
- Average Speed Problems
	- Average speed of v1 and v2 is (d1+d2)/(t1+t2) rather than (v1+v2)/2
- Multiple traveler Problem
	- Example: M and P travelled from A to B at the same time. M travelled at 60mph, and P travelled at 40 mph. When m had arrived at B, P was still 50 miles away. What the distance between A and B?
		- D = 60T, D - 50 = 40T --> T = 2.5, D = 60*2.5 = 150
	- Example2: K drove from A to B at speed of 60mph, turned around, and returned at at 80mph. 4 hours before the end of trip, he was still approaching B, only 15 miles away from B. What is the distance between A and B.
		- From P (point 4 hours ago) to B back A A is 4 hours.
		- Time from P to B is 15/60 = 0.25hr
		- Thus time from B to A is 4 - 0.25 = 3.75
		- Distance = 3.75 * 80 = 300 miles
 - Work Problem
	- Example: Pump x takes 28 hours to fill a pool. PUmp Y takes 21 hours to fill the same pool. How long does it take them to fill the same pool if they are working simultaneously?
		- Rx = 1/28, Ry = 1/21
		- Rxy = Rx + Ry = 1/12

## Problem Solving Strategy
- Backsolving: assuming one of the numerical answers from five options is the correct answer; from this, we work backwards, and see if it make sense in the problem. If the answer doesn't work, we pick another answer and try again.
	- Improvement: choose the middle answer and see the difference is greater or lesser.
- Always check whether the question define the variable to be integers or not.
- If the question ask the question like x + y rather than x = ? or y = ?, there must be a shorter way to get the answer without resolving x and y.
- If one expression is repeated or compound fraction, we can choose a single variable for the expression.
	- (x^2+1)^2 - 15(x^2+1) + 50 = 0 --> u = x^2+2, u^2 - 15u + 50 = 0
	- 3 / (1-8/(7+k)) = 15
- Assign Variable
	- Pick a variable that you can know what the symbol represents.
	- Assign a variable for the smallest value or for the target value for which the question ask. 

## Expression
- **is** or **are** correspond to the **equal sign**
	- A is 50 more than B: A = B + 50
	- A is 50 less than B: A = B - 50
	- Twice A is 100 less than three times B: 2A = 3B - 100
	- A is 50% of B: A = 0.5B
	- A is **50% greater than B**: A = 1.5B
- A is X times as ____ as B, X times as ____ A as B
	- 7 years ago, Samir was 3 times as old as Deepak: S - 7 = 3(D - 7)
	- Sue planted 4 times as many apple seeds as she planted orange seeds: A = 4O