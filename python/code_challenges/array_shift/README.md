# Code Challenege #2

![Whiteboard](./array_shift.png)

## Problem Domain

Write a function called insertShiftArray which takes in an array and a value to be added. Without utilizing any of the built-in methods available to your language, return an array with the new value added at the middle index

## Input/Output

Input = array

Output = array + value that needs to be added to the array, and placed in the correct order of ascending or descending value

## Edge Cases

The following are some reasons why the test may fail based on list:

* The value to be added is an string and the array in an integer.

* array length is 0

* all the values that are in the arry and the value to be added are the same value

## Visual

Input [2,3,4,5], 1

output[2,3,1,4,5]

## Big O

Time <--O(n)
Space <--O(1)

## Algorithm

Define a fx that takes the value to be added and and inserts it into the middle index of the given array array.

Return the array with the inserted value in the middle array of the new array.

## Pusuedo

Use //2  to determine the length of the array.
If the length of the array is 4 then the middle of the array is 4//2. The int to be added will be by using the + operator.

## Code

x = [1,2,3,4,6,7,8,9],5
mid = len(x)//2
x = x[0:mid]+[5]+x[mid:]

print(x)

## Verification

Input
x=[1,2,3,4,6,7,8,9], 5

Output
X = [1,2,3,4,5,6,7,8,9]
