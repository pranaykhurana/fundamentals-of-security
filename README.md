# fundamentals-of-security

In the case of collision free property, there is no restriction on target hash. The approach followed
in the collision.c program to break this property is as follows:

1. Allocated an array for saving hash values
2. Generate initial message (call it M)
3. Find M’s hash
4. Generate random string and find its hash
5. Compare hash from (4) to M’s hash, if a match is found then exit and report the number
of iterations used.
6. Compare hash from (4) to each hash value in array, if any match is found then exit and
report the number of iterations used.
7. If no match is found, save the hash from (4) into the array and go to step (4)
