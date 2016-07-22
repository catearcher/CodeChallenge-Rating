# CodeChallenge-Rating

This is a coding golf challenge in JavaScript from the Socialisten summercamp 2015 #camp404.

In ski jumping, the athletes' jumps are graded by five judges. To prevent them from manipulating the total score of a jumper, the highest and lowest scores are ignored in the result. Only the three middle scores are summed up.

In this challenge, we want to allow an arbitrary number of judges (although anything less than three does not make much sense), as well as arbitrary scores, including floats.

Input: Arbitrary numbers, separated by commas. Example:

```
1,5,9,42,3.1415,99  // output: 59.1415
```
