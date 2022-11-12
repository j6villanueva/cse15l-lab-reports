# Lab Report 4 - Vim

# Part 1
## Change main method to allow the second command line argument to be used for the path to search

### Key Sequence to change main method:
`/techn<Enter>nce<esc>hhxxxxxiargs[1]<esc>:wq`

### 1. First use vim DocSearchServer.java in order to get into the DocSearchServer.java file.
### 2. After, type in each key sequence detailed below:

### * a. `/techn<Enter>` **searches for occurrences of /techn**
![Step1](Lab4-img/Lab4.1.png)
![Step1.1](Lab4-img/Lab4.1.1.png) 

### * b. `n` **Iterate once to the second occcurence of techn.**
![Step2](Lab4-img/Lab4.2.png)

### * c. `ce` **Replace to the end of the current word with nothing.**
 ![Step3](Lab4-img/Lab4.3.png)

### * d. `<esc>` **Exit insert mode.**
 ![Step4](Lab4-img/Lab4.4.png)

### * e. `h h` **Move cursor left twice to the beginning of the parameter input.**
 ![Step5](Lab4-img/Lab4.5.png)



### * f. `x x x x x` **Delete everything in parameter input.**
 ![Step6](Lab4-img/Lab4.6.png)


### * g. `i` **Change to insert mode.**
 ![Step7](Lab4-img/Lab4.7.png)

### * h. `args[1]` **Enter args[1] in the parameter space to allow for the use of the second command-line argument for the path to search.**
 ![Step8](Lab4-img/Lab4.8.png)

### * i. `<esc>` **Exit insert mode and go back to normal mode.**
 ![Step9](Lab4-img/Lab4.9.png)

### * j. `:wq` **Save and quit vim.**
 ![Step10](Lab4-img/Lab4.10.png)
---

# Part 2

## Times, Difficulties
### VScode --> SCP: 3:43
I ran into difficulties remembering the destination to scp to but no biggie on time loss. 

### Directly on server --> Vim: 2:03
I ran into difficulties trying to remember how to navigate Vim again but after pushing some keys the movements came back to me.


## Question 1
### Which of these two styles would you prefer using if you had to work on a program that you were running remotely, and why?

I prefer using Vim direcly on the server out of both styles if I were working on a program remotely. Even though I am not used to using them this was way more convenient as I was already on the server and I didn't have to think further about copying stuff over, logging in the server, and jumping into the correct diretory to run the tests.

## Question 2
### What about the project or task might factor into your decision one way or another? (If nothing would affect your decision, say so and why!)

 If I was changing large amounts of code I would most likely just adjust the files in VS code and SCP them over but for quick fixes I prefer to be on the server and use Vim