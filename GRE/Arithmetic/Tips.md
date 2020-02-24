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

## Statistics
- **Mean** is the average: sum / N, N is the number of entries
	- Sum = N * mean
	- Weighted Average: 
		1. Find Sum
		2. **Average of whole = A1 * P1 + A2 * P2 + A3 * P3, Pn is the proportion of An in all items**
			- In a certain company, 70% of employees are markets who make an average f $40,000; 20% are programmers who make an average of $80,000; and 10% are managers, who make an average of $120,000. What is the average salary of all employees at this company?
				- Average = 0.7 * 40000 + 0.2 * 80000 + 0.1 * 120000 = 1000 * (28 + 16 + 12) = 56000
		3. If there are **only two groups**, the distances from the two group averages to the total average are in a ratio that is the reciprocal of the ratio of the proportions.
- **Median**: the middle of an **ordered** list.
	- If two numbers are in the middle, then we average these two numbers
- **Mode**: the most frequently appearing number
- **Range**(max - min): doesn't tell where most of the points in between are.
- Standard Deviation (SD): deviation from the mean
	- Facts:
		1. Positive or zero, never negative
		2. zero when all numbers are the same.
		3. If all the number are exactly the same distance from the mean, that distance is the SD.
			- list = {2,2,2,8,8,8}, mean = 5, SD = 3
		4. a set with most numbers clustered toward the extreme will have higher SD than a list with most values equal to or close to the mean.
		5. **if we add or subtract the same number to every number on the list, the SD doesn't change.**
		6. **if we multiply every number on a list by number K, the SD also get multiplied by |K|.**

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

## Sequence
- 1 + 2 + 3 + .... + 98 + 99 + 100
	- (1+100) + (2+99) + (3+98) + ... + (50+51)
	- 101 * 50 = 5050
- If we have any **evenly-spaced** list that has N items (N can be odd or even), the sum must be (a1+aN)*N/2
	- What is the sum of all multiples of 20 from 160 to 840 inclusive
		- 160 is 8th term of multiples of 20
		- 840 is 42th term of multiples of 20
		- there is 42 - 8 + 1 = 35 terms in the sequence
		- (160+840) * 35/2 = 1000 * 17.5 = 17500

## Power and Root
- Power Operation:
	- (a^n)(a^m) = a^(n+m)
		- 9^5 * 9*3 = (9 * 9 * 9 * 9 * 9) * (9 * 9 * 9) = 9^8
	- (a^n)/(a^m) = a^(n-m)
	- (a^n)^m = a^(nm)
		- (6^5)^3 = (6 * 6 * 6 * 6 * 6)^3
		- (6 * 6 * 6 * 6 * 6) * (6 * 6 * 6 * 6 * 6) * (6 * 6 * 6 * 6 * 6) = 6^15
	- a^(-n) = 1 / a^n
		- a^(-n) = a^0 / a^n = 1 / a^n
	- (p/q)^-n = (q/p)^n
		- (1/3)^-8 = 3^8
		- (b^5 * d^-8) / (h^-4 * k^7) = (b^5 * h^4)/(d^8 * k^7)
		- (24x^12 * y^9) / (18x^-4 * y^3) = (4/3)x^16 * y^6
	- (ab)^n = a^b * b^n
		- (5*3)^8 = 5^8 * 3^8
	- (a/b)^n = a^b / b^n
- Illegal power operation:
	- (a +- b)^p != a^p +- b^p
- Unit Digit Question
	- Look for repetition of pattern
	- What is the unit digit of 57^123
		- 7^1 = 7. 7^2 = ..9, 7^3 = ..3, 7^4 = ..1, 7^5 = ...7, ......
		- the remainder 123 divided by 4 is 3
		- hence, the unit digit is 3rd term of {7,9,3,1}, 3
- Root
	- If the question ask x^2 = 5, there are two answer {√5, -√5}
	- However, if the question say √36, it must have only one answer, 6.
	- √x^2 = |x|
	- Rough Approximation
		- **√2 = 1.4**
		- **√3 = 1.7**
		- **√5 = 2.2**
	- If b > 1
		- b^2 > b
		- √b < b
	- If 0 < b < 1
		- b^2 < b < 1
		- 1 > √b > b
	- If 0 < a < b < c, then 0 < √a < √b < √c
- Root Operation
	- √(PQ) = √P√Q
	- √(P/Q) = √P / √Q
- Illegal power operation:
	- √P + √Q !== √(P+Q)
	- √P - √Q !== √(P-Q)

## Triangle
- Basic facts
	1. The sum of three angles inside any triangle is 180 degrees.
	2. Angle: a triangle can not have two obtuse angles
		- Acute angle: angle < 90 degrees
		- Right angle: angle = 90 degrees
		- Obtuse angle: angle > 90 degrees
	3. **The largest angle is always opposite the longest side. The smallest angle is always opposite the shortest side.**
	4. Inequality theorem: in any triangle, **the sum of any two sides must be greater than (not equal) the third side.**
	5. By inequality theorem: **P - Q < third side < P + Q** (P, Q is the lengths of other two sides)
- Isosceles Triangle and Equilateral Triangle
	- **Isosceles**: a triangle in which two sides are equal
		- It would have equal angles opposite the equal sides.
		- If a triangle has two equal angles, it must be isosceles.
	- **Equilateral**: three equal sides and three equal angles.
		- All angles are 60 degrees.
		- **The area of an equilateral triangle is (√3*S^2)/4, S is the length of the side**
			- Derived by {30deg, 60deg, 90deg} feature of right triangle
	- 4 special lines
		1. Altitude: a line goes through the vertex and is perpendicular to the opposite "side". The point where it intersects the side usually is not the midpoint of the opposite line.
		2. Perpendicular bisector: not pass through the opposite vertex at all.
		3. Median: A line from a vertex to the midpoint of the opposite side. It does not divide the angle into half.
		4. Angle bisector: a line divide the angle in half, but it doesn't divide the opposite side into half.
- Right Triangle
	- Legs: the two side that meet at the right angle
	- Hypotenuse: the side opposite the right angle. It is always the longest side.
	- **Pythagorean theorem**: a^2 + b^2 = c^2
		- A right triangle can satiate this theorem.
		- If the theorem works for a triangle, the triangle must be a right triangle.
	- **Common Pythagorean triplet**
		- **{1,1,√2}: {45deg, 45deg, 90deg}**
		- {3,4,5}
		- **{1,√3,2}: {30deg, 60deg, 90deg} proofed by equilateral triangles**
		- {5,12,13}
		- {7,24,25}
		- {8,15,17}
- Similar triangle
	- If two triangle has the same angle.
	- All corresponding sides of triangles share a common scale factor k.
	- When the length is multiplied by k, and then the area is multiplied by k^2  

## Quadrilaterals
- The sum of four interior angles is 360deg.
- Parallelogram
	- Properties
		1. Opposite sides are parallel
		2. Opposite sides are equal
		3. Opposite angles are equal
		4. The diagonals bisect each other.
- Rhombus
	- It is equilateral quadrilateral. (Diamond Shape)
	- Properties beside of Parallelogram
		- All four sides are equal
		- Diagonals are perpendicular
- Rectangle
	- Quadrilaterals with four 90deg angles
	- Properties beside of Parallelogram
		- All four angles are equal to 90deg
		- Diagonals are congruent, same length.
- Square
	- All properties of Rhombus and Rectangle
- Trapezoid
	- A trapezoid has exactly one pair of parallel sides (bases).
	- Two angles on a leg are supplementary.
	- Area: (b1+b2)*h/2

## Polygon
- Names: pentagon, hexagon, and octagon
- Diagonals: a vertex has (n - 3) diagonals, n is the number of sides
	- Pentagon: 5 diagonals
	- Hexagon: 9 diagonals
- Angles: 180 * (n-2), n is the number of sides
- Regular polygon
	- Every side has the same length.
	- Every angle is identical.

## Circle
- Features
	- Radius/radii (r): a segment from the center to any point on the circle. 
	- Chord: a segment from two endpoint on the circle. The longest one must be diameter.
	- Diameter (d): A chord pass through the center of the circle. d = 2r
	- Circumference: The length around the whole circle. c = dπ = 2rπ
	- π: an irrational number, equals to 3.14159......, or approximate 3.14 or 22/7
	- Arc: a curved line between two points on the circle
	- Area: a = πr^2
- Primary strategy for circle problems: **find the radius**
- Properties
	- Central Angle: the angle has its vertex at center of the circle 
		- - **Equal length chords in the same circle intersect equal length arcs.**
	- Inscribed angle: the angle has its vertex on the circle 
		- The measure of the inscribed angle is half (1/2) the measure of the arc it intercepts.
		- **Any inscribed angle that intercepts a semicircle has to be a right angle.**
		- **If two inscribed angle in the same circle intercept the same arc of same chord, then the two inscribed angles are equal**
	- A tangent line is perpendicular to a radius at the point of tangency.

## Three-Dimension 
- Cube:
	- Volume = s^3
	- Total area = 6s^2
	- Space Diagonal = s√3
- Rectangular solid
	- Volume = hwd
	- Total Area = 2hw + 2hd + 2wd
	- Space Diagonal = √(width^2 + length^2 + height^2)
- Cylinder
	- Volume: hπr^2 
	- Total Area: 2πr^2 + 2πrh = 2πr(r+h)

## Linear Coordinate
- Horizontal line: y = K
- Vertical line: x = K
- Intercepts
	- An intercept is the point at which a graph crosses the x or y axis.
	- At a y-intercept, the value of x = 0. (0, y)
	- At a x-intercept, the value of y = 0. (x, 0)
- Slope: 
	- Rise over run
		- Run: **horizontal separation** from the left to right.
		- Rise: vertical separation between the points from the left to right. If the point on right is higher, then the rise is positive; if lower, negative.
		- Slope = rise / run = (y2 - y1) / (x2 - x1)
	- Meaning: (if slope = 2)
		- right 1 unit, up 2 unit
		- right k unit, and then up 2k unit.
		- left 1 unit, down 2 unit
		- left k unit, and then down 2k unit.
	- Special slope m
		- If |m| = 1, and then the slope triangle is a 45-45-90 triangle
		- If two line have the same slope, then the two line are parallel.
		- If the product of two slope m1 and m2 is -1, then the two line must be perpendicular.
			- If the slope of original line is m1 = p/q
			- The slope of the perpendicular is m2 = -q/p
		- For horizontal line, m = 0.
		- For vertical line, m is undefined or infinite.
	- Slope-Intercept Form: y = mx + b
		- m is slope
		- b is the y-intercept
- Reflection
	- Reflection over the line y = x: (a,b) reflects (b,a)
	- Reflection over the line y = -x: (a,b) reflects (-b,-a)

## Counting
- And/OR
	- And = multiply
	- Or = add
- Fundamental Strategy
	- If the first stage can be done in n1 ways, the second in n2 ways, then the complete task can be done in N = n1 * n2 * n3 * ... ways.
	- If we have to arrange a set of n different items **in order**, the number of possible orders is the product of n times all the positive integers less than n, **N = n! = n * (n-1) * (n-2) * ... * 1**
	- **When a counting problems contains restrictions in certain stage, always do the most restrictive stage first.**
	- If you are asked to count how many arrangements obey a restriction, it may be easier to count the ones that do not, and subtract them from the total.
		- Clue 1: the word "not".
		- Clue 2: focus on an single item.
- Counting with **identical items (order doesn't matters)**
	- In a set on n items, there were b identical items, and the total number of arrangement is N = n! / b!
	- If there are n items, including one group of b identical items, another group of c identical items, and yet another group of d identical itemsL **N = n! / (b! * c! * d!)**
- **Combination: nCr (n choose r)**
	- 7C1 = 7
	- nC1 = n
	- 10C4 = 10C6 = (10 * 9 * 8 * 7) / (4 * 3 * 2 * 1) = 10!/4!*6! = 210
	- nCr = nC(n-r) = n! / r!*(n-r)!

## Probability
- Rules of Probability
	- P(not A) = 1 - P(A)
	- OR means add
	- AND means multiply
	- **P(A or B) = P(A) + P(B) - P(A and B)**
- If A and B are **mutually exclusive** events, and then P(A and B) = 0
- If A and B are **independent events**, and then **P(A and B) = P(A) * P(B)**
- Conditional Probability: **P(A and B) = P(B) * P(A|B) = P(A) * P(B|A)**
	- If selection that are **"without replacement" are NEVER independent**
- Binomial Situation
	- For some r <= n, what is the probability of exactly r successes in n trials?
	- Examples:
		1. Three fair coins are flipped. What is the probability of getting exactly two heads? (3/8)
		2. Ten dice, each fair with six-sides, are rolled simultaneously. What is the probability of getting exactly two five among them? (1/6)^2 * (5/6)^8 * 10C2
	- General formula
		- p = probability of success on one trial
		- n = number of trials
		- r = number of success
		- P = (nCr) * p^r * (1-p)^(n-r)
- At lest Scenario
	- When you see the words **"at least"** in a probability question, **use the Complement Rule shortcut**.
	- Examples:
		1. Suppose we roll one fair six-sided die eight times. What is the probability we will roll at least one six?
			- The complement of "at least one six" is "zero six"
			- P(at least one six) = 1 - (5/6)^8 6
- Using counting techniques: **P = # of success / total # of outcomes**
- Which technique to use
	- Use the *formal algebraic rules* if
		1. the problem gives you algebraic expressions: P(A) = 0.5, P(B) = 0.6, etc.
		1. the items concerned are coins, cards, dice, etc.
		1. if the language of the problem uses words "mutually exclusive" or "independent"
	- Use the *listing* ONLY IF the full list is vert short, fewer than 10.
	- Use the counting if the problem involves selection of several elements from a set, with certain restrictions.
	- Consider using the Complement Rule when applying algebraic rules or counting techniques.


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
- A is X times as ____ as B, X times as ____ A as B: A = XB
	- 7 years ago, Samir was 3 times as old as Deepak: S - 7 = 3(D - 7)
	- Sue planted 4 times as many apple seeds as she planted orange seeds: A = 4O