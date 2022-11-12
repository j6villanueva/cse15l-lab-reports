# Lab Report 4 - Vim
## Change main method to allow the second command line argument to be used for the path to search

### Key Sequence to change main method:
`/techn<Enter>nce<esc>hhxxxxxiargs[1]<esc>:wq`

### 1. First use vim DocSearchServer.java in order to get into the DocSearchServer.java file.
### 2. After, type in each key sequence detailed below:

###    a. `/techn<Enter>` **searches for occurrences of /techn**

![Step1](Lab4-img/Lab4.1.png)
![Step1.1](Lab4-img/Lab4.1.1.png) 

###    b. `n` **Iterate once to the second occcurence of techn**
 ![Step2](Lab4-img/Lab4.2.png)

###    c. `ce` **Replace to the end of the current word with nothing**
 ![Step3](Lab4-img/Lab4.3.png)

###    d. `<esc>` **Exit insert mode.**
 ![Step4](Lab4-img/Lab4.4.png)

###    e. `h h` **Move cursor left twice to the beginning of the parameter input.**
 ![Step5](Lab4-img/Lab4.5.png)



###    f. `x x x x x` **Delete everything in parameter input**
 ![Step6](Lab4-img/Lab4.6.png)



 ![Step7](Lab4-img/Lab4.7.png)
* Change to insert mode

`i`

 ![Step8](Lab4-img/Lab4.8.png)
* Enter args[1] in the parameter space to allow for the use of the second command-line argument for the path to search

`args[1]`

 ![Step9](Lab4-img/Lab4.9.png)
* Exit insert mode and go back to normal mode

`<esc>`

 ![Step10](Lab4-img/Lab4.10.png)
* Save and quit vim

`:wq`