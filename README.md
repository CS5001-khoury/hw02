# Homework 02 - Introduction to Logic (Option A)

For this module, we will explore both variable types, logic and building flowcharts. This homework let's you practice both with multiple mini-projects.

## Star Rating Version 2

For this task, you will explore variable types and client `input()`.  For this task, you will use [star_rating_v2.py](star_rating_v2.py)

### Part 1: Star Rating  Flowchart

👉🏽 **Task**:  Build a flowchart that maps out the following program. You will submit the flowchart with your code, and you are free to talk about this flowchart. 
However, if you do talk with others on it, make sure their names are included on the flowchart and contribution (e.g. worked in a group).
You should submit the chart as an image either via taking a picture or using a program mentioned in Additional Resources below. 

Your client has asked you to write the following program.

1. Takes in the client's input for both the name of a movie and the number of stars to give it.
2. It will then print to the screen Movie and Stars (*) equal to the number given. 
   1. There will be five spaces between name and stars.
3. If someone enters less than 1 star, 1 star is used, if they enter more than 5, five stars is used. 
4. You do not have to worry about the case if the person doesn't enter a number.
5. If they enter a partial number, round down.  (1.5 becomes 1 star)

They have provided the following samples.

```text
Enter a movie: Thor
Rate between 1 and 5: 3
Thor     ***
```

```text
Enter a movie: Princess Bride
Rate between 1 and 5: 5
Princess Bride     *****
```

### Part 2: Write the Program

👉🏽 **Task**: Using your flowchart as a guide, write the program using the template [star_rating_v2.py](star_rating_v2.py).



## Location Guessing Application

For this task, you will explore variable types, client `input()`, and boolean logic. For this, you will use [temp_guess.py](temp_guess.py)

You will write an application that suggests a location to live based on conditions.

Given the following chart

| City | High | Low |
| :-- | :--: | :--: |
| Beijing | 33 | -8 |
| Boston | 28 | -7 |
| Honolulu | 32 | 13 |
| San Francisco | 27 | 6 |
| Vancouver BC | 24  | 2 |

* The client will provide two numbers, a high and low number. 
  * They can be in any order, it is safe to assume the lower number is their low, and the higher is their high
* Based on the high and low, will provide recommendations based on locations that fall within the range provided. 
 
For example, 
```text
Enter a temperature: 33
Enter a second temperature: -8
Beijing
```

```text
Enter a temperature: 28
Enter a second temperature: -10
Boston
San Francisco
Vancouver
```

```text
Enter a temperature: 12
Enter a second temperature: 35
Honolulu
```

```text
Enter a temperature: 0
Enter a second temperature: 30
San Francisco
Vancouver
```

```text
Enter a temperature: 0
Enter a second temperature: 20
Unknown
```


If a condition can't be met, it will print Unknown. You may find it easier to build a string first, and then print the final string. You do not have to worry about an extra line at the bottom of the print.

A flowchart is not required for submission, but it is **highly** recommended you write one! It is also recommended you test as you write to make sure you have the correct signs on your condition checks. 


## README.md

You should create a readme file that contains the following information

* Reflection of what you learned this module, include what you think you need to work on and how you will improve those skills
* List any coding practice problems you did  - not required, but we are curious. 
* Your answer to the following further thinking problem 

### Further Thinking: Guessing Numbers

Assume you are writing a guessing game application in which the computer generates a random number, and you get to keep guessing until you find the number. You know the number is between 1 and 100.

* Can you come up with an algorithm to guess the correct number? As you have as many changes as possible, it is alright to do the simplest case. 
* Assuming there are 100 possible numbers, how many guesses would it take in the worst case?
* Now, can you figure out an algorithm that would take less guesses in the worst case and still come up with the same answer?
  * This is challenging! do the best you can, talk with others, and no need to have the correct answer at this time - just any answer will be valid)
  * 



## Grading Rubric


Add (AG) and (MG) next to tiers, add major conditions to meet to pass each tier. 

1. Learning ()
   * 
2. Approaching  ()
   * 
3. Meets  ()
   * 
4. Exceeds  ()
   * 


AG - Auto-graded  
MG - Manually graded


## Additional Resources (optional)

### `input()` reminder

### Drawing flowcharts

