# Armstrong Number

An Armstrong number is a number that is the sum of its own digits each raised to the power of the number of digits. This definition depends on the base `b` of the number system used, e.g., b = 10 for the decimal system or b = 2 for the binary system. It was named after  Michael F. Armstrong. They are also called as *narcissistic number* , *pluperfect digital invariant*  or a *plus perfect number*.In easy words we can say, An `n` -digit number equal to the sum of the `n`<sup>`th`</sup>  powers of its digits. As:-

 `abcd... = pow(a,n) + pow(b,n) + pow(c,n) + pow(d,n) + ....`

Eg. 153 = 1<sup>3</sup> + 5<sup>3</sup> + 3<sup>3</sup>

## Definition

The definition of a Armstrong number relies on the decimal representation n = d<sub>k</sub>d<sup>k-1</sup>...d<sub>1</sub> of a natural number n, i.e.,

n = d<sub>k</sub>·10<sup>k-1</sup> + d<sub>k-1</sub>·10<sup>k-2</sup> + ... + d<sub>2</sub>·10 + d<sub>1</sub>,
with k digits d<sub>i</sub>  satisfying 0 ≤ d<sub>i</sub> ≤ 9. Such a number n is called Armstrong if it satisfies the condition

n = d<sub>k</sub><sup>k</sup> + d<sub>k-1</sub><sup>k</sup> + ... + d<sub>2</sub><sup>k</sup> + d<sub>1</sub><sup>k</sup>.

## Some Armstrong Number 

* The sequence of base 10 Armstrong numbers starts: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 153, 370, 371, 407, 1634, 8208, 9474, ...
* The sequence of base 8 Armstrong numbers starts: 0, 1, 2, 3, 4, 5, 6, 7, 24, 64, 134, 205, 463, 660, 661,..
* The sequence of base 12 Armstrong numbers starts: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, ᘔ, Ɛ, 25, ᘔ5, 577, 668, ᘔ83,.. 
* The sequence of base 16 Armstrong numbers starts: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F, 156, 173, 208, 248, 285, 4A5, 5B0, 5B1, 60B, 64B, ...
* The sequence of base 3 Armstrong numbers starts: 0, 1, 2, 12, 22, 122The sequence of base 4 Armstrong numbers starts: 0, 1, 2, 3, 130, 131, 203, 223, 313, 332, 1103, 3303 
* In base 2, the only Armstrong numbers are 0 and 1.

## Interesting Fact

In 1993 Hardy  wrote, "There are just four numbers, after unity, which are the sums of the cubes of their digits. These are odd facts, very suitable for puzzle columns and likely to amuse amateurs, but there is nothing in them which appeals to the mathematician."

