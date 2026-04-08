# JS-Assignment
questions on JS
question 1-
Approach : is to loop through every number from L to R and check it against all the given conditions. For each number first verify that it is divisible by K. Then we examine its digits to ensure it does not contain the digit 0, while also calculating the sum of its digits. After that check whether this digit sum is a prime number. If a number satisfies all these conditions, we count it. Since we may check up to 10⁶ numbers and each number has only a few digits

total time complexity is approximately O(n*d), where d is number of digits and n is range 
the space complexity is O(1) because only constant extra space is used.

question 2-
Approach is to start with the given integer N and repeatedly update it for exactly three iterations based on its parity. In each iteration, if the current value is even, it is replaced by (current ÷ 2 + seed); otherwise, it is replaced by (current × 3 − seed). After completing three transformations, the final value is checked to see whether it lies between 100 and 999 inclusive. If it does, the middle digit of this three-digit number is extracted and compared with the seed. If both conditions hold, the output is YES; otherwise, the output is NO.
Time Complexity: O(1)

question 3-
approach 
Initialize X = 0
 Loop while X ≤ 100000
 Compute value = N + X
 Check if value is a palindrome
 Check if value % K == 0
 If both conditions are satisfied → print X and stop
 Else increment X by 1 and continue
 If loop ends without finding valid X → print -1

Time Complexity: O(N * d)

questtion 4-
Initialize fare = base + 7 × distance
 If minutesLate > 15 → fare = fare + 20
 If distance > 10 → add ⌊0.10 × fare⌋ to fare
 If seed is odd → fare = fare − seed
 Else → fare = fare + seed
 Round fare up to the nearest multiple of 5
 Print the final fare
 Time Complexity: O(1)

question 5-
Set m = 1, sum = 0
approach
 While sum < N
 If m % (seed + 2) ≠ 0 → add m to sum
 Increment m
 After loop, output m − 1 and sum
 Time Complexity: O(N)

question 6-
Approach
 Read values `a`, `b`, `c`
 Compute `score = 3a + b − 2c`
 If `score < 0` → set `score = 0`
 If `a + b + c > 50` → `score = score − 10`
 If `score ≥ 60` → status = Pass
 Else → status = Fail
 Output final `score` and `status`

 Time Complexity: O(1)



