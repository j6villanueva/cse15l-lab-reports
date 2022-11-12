# Lab Report 4 - Vim
# Change main method to allow the second command line argument to be used for the path to search

 ![Step1](Lab4-img/Lab4.1.png)
* Open DocSearchServer in Vim

`vim DocSearchServer.java`

 ![Step2](Lab4-img/Lab4.2.png)
* Search for occurrences of /techn 

`/techn<Enter>`

 ![Step3](Lab4-img/Lab4.3.png)
* Iterate once to the second occcurence of techn

`n`

 ![Step4](Lab4-img/Lab4.4.png)
* Replace to the end of the current word with nothing

`ce`

 ![Step5](Lab4-img/Lab4.5.png)
* Exit insert mode

`<esc>`

 ![Step6](Lab4-img/Lab4.6.png)
* Move cursor left twice to the beginning of the parameter input

`h h`

 ![Step7](Lab4-img/Lab4.7.png)
* Delete everything in parameter input

`x x x x x`

 ![Step8](Lab4-img/Lab4.8.png)
* Change to insert mode

`i`

 ![Step9](Lab4-img/Lab4.9.png)
* Enter args[1] in the parameter space to allow for the use of the second command-line argument for the path to search

`args[1]`

 ![Step10](Lab4-img/Lab4.10.png)
* Exit insert mode and go back to normal mode

`<esc>`

 ![Step11](Lab4-img/Lab4.11.png)
* Save and quit vim

`:wq`