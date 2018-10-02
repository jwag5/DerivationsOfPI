# DerivationsOfPI
Some infamous numerical methods for estimating the value of PI

Machin's Pi:
This program is an implementation of the Series Format of <a href="http://www.pi314.net/eng/machin.php">Machin's Formula</a> for pi = 16arctan(1/5) - 4arctan(1/239). He discovered this in the early 1700s and was able to calculate 100 digits of pi using it! 

Kashi's Pi:
This is a short program to implement Kashi's Method for determining PI. Its derived from an ingenious method of inscirbing larger and larger n-sided polygons inside a circle to calculate more and more accurate digits of pi. I highly recomend investigating this thoerem and proof further, but it simplifies beautifuly to a recursive relation we can use to compute the chord created by the n-sided polygon and the arc this chord creates.

C_n = (2 + C_n-1)^1/2

a_n = (4 - C_n^2)^1/2
