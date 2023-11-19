# Recursive function palindrome Algorithm

> A word is a palindrome if it can be read from left to right and right to left.The ALgorithm test for palindrome.

## Steps
1. The first loop creates the key/value pairs for each letter.The variable obj creates an empty object in which we will store the letter as the key and the number of occurences as the value.

2. the conditional inside the loop creates a new key/value pair with the value set to 1 or increment the value if the key already exists.

3. Variable countValue is an array of the values from the variable obj.countValue is then iterated over to collect only the odd number of occurences which is stored in the variable oddCount.