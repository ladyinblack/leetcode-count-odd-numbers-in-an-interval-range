### [leetcode-count-odd-numbers-in-an-interval-range](https://leetcode.com/problems/count-odd-numbers-in-an-interval-range/)

## PROBLEM STATEMENT

Given two non-negative itnegers `low` and `high`.  Return the *count of odd numbers between `low` and `high` (inclusive)*.

#### Example 1:
```
Input: low = 3, high = 7
Output: 3
Explanation: The odd numbers between 3 and 7 are [3,5,7].
```

#### Example 2:
```
__Input:__ low = 8, high = 10
Output: 1
Explanation: The odd numbers between 8 and 10 are [9].
```

#### Constraints:
- `0 <= low <= high <= 10^9`

### My Feedback
I found this challenge, for one easy, and two when submitting the test code kept failing due to time limit exceeding.  I removed the curly brackets as they were not necessary to have seeing as the code within the blocks were one line.  I tested this once in JavaScript, and four times in C#.  The first two C# attempts, first attempt didn't pass, second attempt I removed the curly brackets and code was Accepted.  Logged in as a different user the next day, and did the exact same code, but the Time Limit not only exceeds, the time limit for the test sample input is taking longer than it did in the previous user login.

