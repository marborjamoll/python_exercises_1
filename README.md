# Python Exercises
## Review Questions
1. Why is the following the case?
    > print 4 + 9 

    > 13

2. Why is the following the case – rather than the result being 13?
    > print "4 + 9" 

    > 4+9

3. Why does the expression 
    > print 2 + 3 * 4 

    > 14 
    
    and not the value 20?

4. Write a program to accept a string from the user and display characters that are present at an even index number.

    For example, 
    > str = "pynative" 
    
    so you should display ‘p’, ‘n’, ‘t’, ‘v’.

5. Write a program to remove characters from a string starting from zero up to n and return a new string.

    For example,

    > remove_chars("pynative", 4) 
    
    so output must be
    > tive. 
    
    Here, we need to remove the first four characters from a string.

    > remove_chars("pynative", 2) 
    
    so output must be 
    > native. 
    
    Here, we need to remove the first two characters from a string.
    **Note**: n must be less than the length of the string.

6. Write a function to return True if the first and last number of a given list is same. If numbers are different then return False.
    
    Given,
    > numbers_x = [10, 20, 30, 40, 10]

    Output:
    > result is True



    Given, 
    > numbers_y = [75, 65, 35, 75, 30]

    Output:
    > result is False

7. Iterate the given list of numbers and print only those numbers which are divisible by 5.
    ```
    Given list is  [10, 20, 33, 46, 55]
    Divisible by 5
    10
    20
    55
    ```

8. Write a program to find how many times substring “Emma” appears in the given string.

    Given, 
    > str_x = "Emma is good developer. Emma is a writer"
    
    Output:
    > Emma appeared 2 times

9. Write a program to check if the given number is a palindrome number.

    A palindrome number is a number that is the same after reverse. For example, 545, is the palindrome numbers.

    ```
    original number 121
    Yes. given number is palindrome number

    original number 125
    No. given number is not palindrome number
    ```
    
10. Given two list of numbers, write a program to create a new list such that the new list should contain odd numbers from the first list and even numbers from the second list.

    Given,

    ```
    list1 = [10, 20, 25, 30, 35]
    list2 = [40, 45, 60, 75, 90]
    ```

    Expected Output:

    ```
    result list: [25, 35, 40, 60, 90]
    ```

11.  Write a Program to extract each digit from an integer in the reverse order. For example, If the given int is `7536`, the output shall be `“6 3 5 7“`, with a space separating the digits.

12. Print multiplication table from 1 to 10.

13. Write a function called exponent(base, exp) that returns an int value of base raises to the power of exp. Note here exp is a non-negative integer, and the base is an integer.

    Expeted output:

    Case 1

    ```
    base = 2
    exponent = 5

    2 raises to the power of 5: 32 i.e. (2 *2 * 2 *2 *2 = 32)
    ```

    Case 2

    ```
    base = 5
    exponent = 4

    5 raises to the power of 4 is: 625 i.e. (5 *5 * 5 *5 = 625)   
    ```

14. 