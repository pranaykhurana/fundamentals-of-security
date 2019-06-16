# fundamentals-of-security

The program's objective is to hit a "target" hash value by generating the hash for different strings
and matching it with the target hash value(md5).

The approach to generate strings and match them against a target is implemented as follows:
1. Start with string length 1
2. Generate all possible combinations of strings for current length using the character set,
generate its hash and compare it with the target hash.
3. If a match is found, the execution stops and reports the number of iterations used.
4. If no match is found in all possible strings of current length, increment length by ‘1’ and
go to step (2)
