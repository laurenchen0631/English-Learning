## General
- To get a squared number which ends with 5, we slice 5 from the number and multiple it with its increment with 1, and postfix the result with 25.
	- 35^2 = (3 * 4), 25 = 1225
	- 75 * 75 = (7 * 8), 25 = 5625
	- 115 * 115 = (11 * 12), 25 = 13225
- To get (n+1)^2, if we know n^2, we add n and (n+1) to n^2, and then the result will be (n+1)^2
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
- numerator: a/b, a is numerator
- denominator: a/b, b is denominator
- absolute value: the distance of a number from the origin. |0| = 0
- factor, divisor, divisible: If A, B, C are all integers, A*B = C
	- A and B is the factor of C.
	- A and B is the divisor of C.
	- C is divisible by A or B.

## Fraction
- if a > b and a&b are numerator, then (a/c) > (b/c)
- if p > q and p&q > 0 and are denominator. then (s/p) < (s/q)
- Cross multiplication: a/b = c/d --> ad = bc
- Comparison using cross multiplication
	- (7/11) ? (5/8) --> 56 ? 55 --> (7/11) > (5/8)
	- (9/20) ? (4/9) --> 81 > 80 --> (9/20) > (4/9)
- If we add a number p to the numerator and a number q to the denominator, the result will get close to p/q.
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

## Divisibility
- How to find all factor of a large number?
	- 2400 = 24 * 100 = 8 * 3 * 25 * 4 = 2^5 * 3 * 5^2, the number of factor = (5+1) * (1+1) * (2+1) = 6 * 2 * 3 = 36
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