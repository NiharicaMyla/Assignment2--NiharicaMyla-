# Assignment2--NiharicaMyla

# Heading: Niharica Myla
###### Silicy, England is my favourite place in the world.

Italy's largest island, Sicily offers exceptional *beaches, charming villages* and towns, as well as an abundance of **ancient ruins and archeological sites** aces the warm waters of the Mediterranean. Throughout history, ***Sicily has been at the crossroad of cultures, landscapes and cuisine***.

**********

## Section with an ordered list:

Directions to travel from Maryville, MO to St.Louis MO.

1. From Maryville, head west on E 1st St toward N Main st.<br>
2. Turn left onto US-71 BUS S/S Main St.<br>
3. Take the ramp to US -71S and use the left lane to take he I-29 S/US-71 S exit toward    US-59/ Kansas city.<br>
>>Nested!
4. Merge onto I-29 S/US-71 S and keep left at the fork to continue on I-29 S.<br>
    1. Keep left to continue on US-71.<br>
    2. Keep left at the fork to continue on I-70 E/us-40 E, follow signs for St.Louis.<br>
    3. Keep left to continue on I-70 E.<br>
5. Take exit 210A for US-40 E/US-61 S toward Chesterfield.<br>
6. Keep right to continue on I-64 E.<br>
7. Take exit 39A for 14th St.<br>
8. Turn left onto S 14th t.<br>
9. Turn right and then after 350 ft, turn left to reach the destination-St.Louis.<br> 

**Unordered list**

items that should be brought to your favorite place for maximum enjoyment:

- Your photo ID and Passport.
- Phone charger.
- Cash.
- Travel documentation.
- Walking guide.
- General Hygiene Products:
	- Sunscreen.
	- Toothpaste and toothbrush.
	- Antibiotics.
- First aid and umbrella.
- Camera.
- Light backpack.

[link to aboutme.md](https://github.com/NiharicaMyla/Assignment2-NiharicaMyla/blob/main/AboutMe.md)

*********
## TABLES:

The table below shows the list of food items and the drinks that are available to everyone and definitely recommended to try. The table also includes the location of the item and the amount to pay for an item.

| Food item | Location of the item | Amount to Pay |
|:--------:|:--------:|:----------:|
|Yogurt | Walmart |  $2.50 |
| Milk | Dollar General | $3.87 |
| Cheese Burger | McDonalds | $4.00 |
| Pizza | DG | $4.48 |
| Wine | Walmart | $10.98 |

-------------------

# Pithy Quotes:

> Be Brave, Be Strong and Courageous. Do not be Afraid. Do not be Discourage, for the Lord will be with you wherever you go- *Joshua 1:9*.

> The Art of Being Happy is to be Satisfied with what you have - *Terry Brown*.

> Some cause happiness wherever they go; others whenever they go - * Oscar Wilde*.

------------

# Head Fencing:

> Trial division is the most laborious but easiest to understand of the integer factorization algorithms. The essential idea behind trial division tests to see if an integer n, the integer to be factored, can be divided by each number in turn that is less than n. For example, for the integer n = 12, the only numbers that divide it are 1, 2, 3, 4, 6, 12. Selecting only the largest powers of primes in this list gives that 12 = 3 × 4 = 3 × 22. Trial division was first described by Fibonacci in his book Liber Abaci.

Quick link for the source: <https://en.wikipedia.org/wiki/Trial_division>

Here is the code to find `a prime factorization` using `Trial division`.

```
vector<long long> trial_division1(long long n) {
    vector<long long> factorization;
    for (long long d = 2; d * d <= n; d++) {
        while (n % d == 0) {
            factorization.push_back(d);
            n /= d;
        }
    }
    if (n > 1)
        factorization.push_back(n);
    return factorization;
}
```
Quick link for the source code: <https://cp-algorithms.com/algebra/factorization.html>
