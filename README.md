`ECE2112: Advanced Computer Programming and Algorithms`
## EXPERIMENT 1: INTRODUCTION TO PYTHON PROGRAMMING

### I. Intended Learning Outcomes:

1. Too identify the basic codes and functions in Python Programming.
2. To be able to apply  the different codes and functions in creating a Python program.


### II. Instructions:

Write a Python script/code in the Jupyter Notebook to do the given problems. You may submit your Jupyter Notebook in the dedicated submission bin.


### III. Problems:
## ALPHABET SOUP PROBLEM
Create a function that takes a string and return a string with its letters in alphabetical order.

  - To solve a problem, the program accepts a string input and tries to rearrange all of its letters alphabetically. First, the string breaks into individual characters and sorts them from A to Z. After sorting, they merge into a string without a space. Then, the program shows this new alphabetically ordered output string. For example, for "hello," the output would be "ehllo," with the letters all in order.

**Input: text(string)**   
**Output:  sorted string**

```
Pseudocode:
1. Receive Text.
2. Turn the text into a list of characters.
3. Sort that list of characters in ascending order.
4. Join the sorted characters back into a string.
5. Print the result.
```

## EMOTICON PROBLEM
Create a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin, sad, and mad with their corresponding emoticon.

- The Emotify Problem requires the program to take a complete sentence as input. The job is to search for the words smile, grin, sad, and mad, and replace them with the respective emoticons. In doing this, the program scans the sentence, and each time we input any of the mentioned words, the correct emoticon is substituted, like "smile" and replaced by ":)". After substituting the emoticons for every instance found, the program outputs the modified sentence to the user. For example, the sentence "Make me smile" would thus become "Make me :)", "I am mad" changes to "I am >:(". That means we replace only those few words, leaving the entire sentence untouched.

**Input: text(string)**  
**Output:  sorted string**

```
Pseudocode:
1. Receive sentence. 
2. Replace "smile" with ":)"
3. Replace "grin" with ":D"
4. Replace "sad" with ":("
5. Replace "mad" with ">:("
6. Print the result.
```

## UNPACKING LIST PROBLEM
Unpack the list writeyourcodehere into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then print all three variables.

- In the Unpacking List problem, the program provides a list of numbers. The goal is to divide this list into three parts: the first item, the last item, and everything else, which is in between or the middle. To do this, the program takes the first item from the list and saves it in a variable first, takes the last element and keeps it somewhere for later use, and finally saves all the other elements into a middle list. When done, all the input parts will be printed clearly in a message. For example, if the input list were [1, 2, 3, 4, 5, 6], the output would read first: 1, middle: [2, 3, 4, 5], and last: 6.

**Input: writeyourcodehere (list)**  
**Output:  print first: X, middle: [..], last: Y**

```
Pseudocode:
1. Receive  writeyourcodehere.
2. Do first, *middle, last = writeyourcodehere.
3. Print first:,middle:,last:.
```

**Harvey Aaron E. Orzal**  
**2ECE - B**




