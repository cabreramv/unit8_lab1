# Lab Reflection: Unit 8 Lab 1 - Git Version Control + Debugging (BuggyProgram)

## Student Name
Miguel Cabrera

## GitHub Repository URL
https://github.com/cabreramv/unit8_lab1.git

---

# Commit 1: Initial Commit

## What did you include in this commit?
- 

## What was the purpose of this commit?
-

---

# Commit 2: Task 1 (getGrade)

## Which tests in Task1Test were failing before your fix?
- the outputs were wrong

## What was the issue in the code?
- score 90 was assigned meets and score 80 was assigned exceeds.
- it also didnt include 90 and 80.

## What change did you make to fix it?
- Swapped meets and exceeds. Added = to the >.

## How did the tests help guide your fix?
- it showed me what inputs it was using to test the method.

---

# Commit 3: Task 2 (sumEvenNumbers)

## Which tests in Task2Test were failing before your fix?
- Not sure

## What was the issue in the code?
- The array was out of bounds.

## What change did you make to fix it?
- initialized some to 0 instead of 1. 
- changed i <= values.length to i < values.length

## How did the tests help guide your fix?
- It helped guide me to the issue

---

# Commit 4: Task 3 (sumRange)

## Which tests in Task3Test were failing before your fix?
- assertion fail error

## What was the issue in the code?
- the logic in adding the sum was incorrect. I also added an if statement to handle inputs where the start 
- was greater than the end.

## What change did you make to fix it?
- I changed 'sum += i' to 'sum = sum + i'.
- I also added an if statement.

## How did the tests help guide your fix?
- I guess it pointed me in the right direction.

---

# Overall Reflection

## Which task was the easiest to fix? Why?
- I think the easiest was the get grade because the errors stood out to me pretty clearly.

## Which task was the most difficult? Why?
- The most difficult task for me was handling the reverse values for the sumRanges method. I had an idea of the issue
- and didn't want to rely on the internet for the fix so i spent quite some time trying to figure it out.

## How did Git help you track your progress through the debugging process?
- it saved previous versions and if i completely lost the project or made a drastic change that ruined a lot of things
- I could go into git and get a previous version.

## Why is it important to make small, frequent commits when debugging code?
- So when I need to go back to a previous version it has more of the recent changes and I could spend less time 
- rewriting code that didn't need to be rewritten.

## What did you learn about using JUnit tests to guide debugging?
- I guess just reading what populates in the lower box.

---

# Commit 5: Final Reflection

## What did you complete or update before making this final commit?
- I updated the README and completed the last method in BuggyProgram.

## Why is it useful to document your work after completing a programming task?
- it helps when collaborating with others and helps reinforce learning