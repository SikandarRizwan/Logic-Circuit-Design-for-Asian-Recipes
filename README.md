Logic Circuit Design for an Asian Recipe Selector
This repository contains a digital logic circuit design project that acts as a selector for different ingredients based on a user's chosen dish. The project demonstrates an understanding of Boolean algebra, truth tables, and circuit simplification using Karnaugh maps.

Design Breakdown
Inputs (A, B, C): These three binary inputs represent one of the eight possible dishes.

Outputs (Y1-Y10): Each output corresponds to a specific ingredient required for the selected dish.

Truth Tables and Boolean Expressions
Y1 (Rice)
A	B	C	Y1 (Rice)
0	0	0	1
0	0	1	0
0	1	0	1
0	1	1	0
1	0	0	0
1	0	1	1
1	1	0	0
1	1	1	1

Export to Sheets
Boolean Expression: Y1 = A'B'C' + A'BC' + AB'C + ABC

Y2 (Noodle)
A	B	C	Y2 (Noodle)
0	0	0	0
0	0	1	1
0	1	0	0
0	1	1	1
1	0	0	1
1	0	1	0
1	1	0	1
1	1	1	0

Export to Sheets
Boolean Expression: Y2 = A'B'C + A'BC + AB'C' + ABC'

Y3 (Soy Sauce)
A	B	C	Y3 (Soy Sauce)
0	0	0	1
0	0	1	1
0	1	0	1
0	1	1	1
1	0	0	1
1	0	1	1
1	1	0	1
1	1	1	1

Export to Sheets
Boolean Expression: Y3 = 1 (Simplified, as Soy Sauce is used in all dishes)

Y4 (Spring Onion)
A	B	C	Y4 (Spring Onion)
0	0	0	1
0	0	1	1
0	1	0	1
0	1	1	1
1	0	0	1
1	0	1	1
1	1	0	1
1	1	1	1

Export to Sheets
Boolean Expression: Y4 = 1 (Simplified, as Spring Onion is used in all dishes)

Y5 (Pepper)
A	B	C	Y5 (Pepper)
0	0	0	0
0	0	1	1
0	1	0	0
0	1	1	0
1	0	0	1
1	0	1	1
1	1	0	1
1	1	1	1

Export to Sheets
Boolean Expression: Y5 = A'B'C + AB'C' + AB'C + ABC' + ABC

Y6 (Egg)
A	B	C	Y6 (Egg)
0	0	0	1
0	0	1	0
0	1	0	1
0	1	1	0
1	0	0	0
1	0	1	0
1	1	0	0
1	1	1	1

Export to Sheets
Boolean Expression: Y6 = A'B'C' + A'BC' + ABC

Y7 (Beef)
A	B	C	Y7 (Beef)
0	0	0	0
0	0	1	0
0	1	0	1
0	1	1	0
1	0	0	0
1	0	1	0
1	1	0	0
1	1	1	0

Export to Sheets
Boolean Expression: Y7 = A'BC'

Y8 (Pork)
A	B	C	Y8 (Pork)
0	0	0	1
0	0	1	0
0	1	0	0
0	1	1	1
1	0	0	0
1	0	1	0
1	1	0	0
1	1	1	0

Export to Sheets
Boolean Expression: Y8 = A'B'C' + A'BC

Y9 (Fish)
A	B	C	Y9 (Fish)
0	0	0	0
0	0	1	0
0	1	0	0
0	1	1	0
1	0	0	0
1	0	1	1
1	1	0	0
1	1	1	0

Export to Sheets
Boolean Expression: Y9 = AB'C

Y10 (Bean Sprouts)
A	B	C	Y10 (Bean Sprouts)
0	0	0	0
0	0	1	1
0	1	0	0
0	1	1	1
1	0	0	0
1	0	1	0
1	1	0	1
1	1	1	0

Export to Sheets
Boolean Expression: Y10 = A'B'C + A'BC + ABC'
