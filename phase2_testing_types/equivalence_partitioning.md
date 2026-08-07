Part A — Equivalence Partitioning
Username (3–15)

You wrote:

2
7
20

✅ Perfect.

These represent:

Class	Representative
Invalid (<3)	2
Valid (3–15)	7
Invalid (>15)	20

Exactly what I expected.

Password (8–20)

You wrote

5
13
25

✅ Correct.

Age (18–60)
10
40
70

✅ Correct.

OTP (Exactly 6 digits)

You wrote

3
6
10

This is almost correct.

Let's think carefully.

Requirement:

OTP = Exactly 6 digits

Notice it doesn't say

1–6

It says

Exactly 6

So the classes become

Class	Example
Less than 6 digits	123
Exactly 6 digits	123456
More than 6 digits	1234567

The important point is digits, not the numeric value.

If someone enters:

000123

That's still 6 digits.

A lot of beginners confuse "number" with "length."

