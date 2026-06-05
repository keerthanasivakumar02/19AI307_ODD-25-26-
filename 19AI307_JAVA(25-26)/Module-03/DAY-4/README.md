Skip to content
AnkithaMopuri
19AI307_ODD-25-26-
Repository navigation
Code
Pull requests
Actions
Projects
Security and quality
Insights
You’re making changes in a project you don’t have write access to. Submitting a change will write it to a new branch in your fork keerthanasivakumar02/19AI307_ODD-25-26-, so you can send a pull request.
19AI307_ODD-25-26-/19AI307_JAVA(25-26)/Module-03/DAY-4
/
README.md
in
main

Edit

Preview
Indent mode

Spaces
Indent size

2
Line wrap mode

Soft wrap
Editing README.md file contents
  1
  2
  3
  4
  5
  6
  7
  8
  9
 10
 11
 12
 13
 14
 15
 16
 17
 18
 19
 20
 21
 22
 23
 24
 25
 26
 27
 28
 29
 30
 31
 32
 33
 34
 35
 36
 37
 38
 39
 40
 41
 42
 43
 44
 45
# Ex.No:3(D)    INTERFACE 

## QUESTION:
Each judge uses different criteria to score fighters. Based on points, the judge will declare “WIN”, “LOSE” or “DRAW”.

LenientJudge: WIN if diff ≥ 5, DRAW if < 5

StrictJudge: WIN if diff ≥ 10, DRAW if < 10
## AIM:


## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create an interface Judge with an abstract method getResult(int fighter1, int fighter2).
4. Create two classes LenientJudge and StrictJudge implementing the interface and applying different scoring criteria.
5. Accept points scored by two fighters from the user.
6. Accept judge type from the user and invoke the respective implementation.
7. Display the result as WIN, LOSE, or DRAW.
8.Stop the program.

## PROGRAM:
 ```
/*
Program to implement a Interface using Java
Developed by: KEERTHANA S
RegisterNumber:212223040092
*/
```

## SOURCE CODE:
```
import java.util.*;

interface Judge {
    String decide(int p1, int p2);
}

class LenientJudge implements Judge {
    public String decide(int p1, int p2) {
        int diff = Math.abs(p1 - p2);
        if (p1 > p2 && diff >= 5)
            return "WIN";
        else if (p2 > p1 && diff >= 5)
            return "LOSE";
Use Control + Shift + m to toggle the tab key moving focus. Alternatively, use esc then tab to move to the next interactive element on the page.
No file chosen
Attach files by dragging & dropping, selecting or pasting them.
