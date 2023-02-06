If you're like me, finding the right size t-shirt can sometimes be a challenge. What size am I? What's the difference between S (small), M (medium), and L (large)? I usually wear L, but what if I need an XL (extra large)?

Thankfully, our friends at Teespring have got us covered because they've created a sizing chart to make things a lot easier.

T-Shirt Sizing Chart
Size	Width	Length	Sleeve
S	18"	28"	8.13"
M	20"	29"	8.38"
L	22"	30"	8.63"
XL	24"	31"	8.88"
2XL	26"	33"	9.63"
3XL	28"	34"	10.13"
Source: Teespring.com

Directions:
Use the sizing chart above, create a series of logical expressions that prints the size of a t-shirt based on the measurements of shirtWidth, shirtLength, and shirtSleeve. Valid sizes include S, M, L, XL, 2XL, and 3XL.

For example, if...

const shirtWidth = 23; // size L (large)
const shirtLength = 30; // size L (large)
const shirtSleeve = 8.71; // size L (large)
Then print L to the console.

Hint: You will need to compare a range of values when checking for shirtWidth, shirtLength, and shirtSleeve. For example, if the shirt's width is at least 20", but no more than 22", then the t-shirt should be medium (M) — as long as the other values for the shirt's length and sleeve measurements match up.

If shirtWidth, shirtLength, and shirtSleeve don't fit within the range of acceptable values for a specific size, then print NA to the console. For example, if...

const shirtWidth = 18; // size S (small)
const shirtLength = 29; // size M (medium)
const shirtSleeve = 8.47; // size M (medium)
Then print N/A to the console because the measurements don't all match up with one particular size.

Running Your Code
Enter the following in the terminal:

node what-wear.js
Testing Your Code
How will you know if your code works? Change the values of shirtWidth, shirtLength and shirtSleeve and re-run the code and compare your output with the expected output.

Expected Output
Width	Length	Sleeve	Size
18	28	8.13	S
19.99	28.99	8.379	S
20	29	8.38	M
22	30	8.63	L
24	31	8.88	XL
26	33	9.63	2XL
27.99	33.99	10.129	2XL
28	34	10.13	3XL
18	29	8.47	NA