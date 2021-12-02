# get_next_line
```c
  char *get_next_line(int fd);
```
<div><p>The goal of this project is to create a function that reads a file descriptor and returns a line.</p>
<ul>
  <li>Calling your function get_next_line in a loop will then allow you to read the text
available on the file descriptor one line at a time until the end of it.</li>
  <li>Your function should return the line that has just been read. If there is nothing else to read or if an error has occurred it should return NULL.</li>
  <li>Make sure that your function behaves well when it reads from a file and when it reads from the standard input.</li>
  <li>libft is not allowed for this project. You must add a get_next_line_utils.c file which will contain the functions that are needed for your get_next_line to work.</li>
 </ul></div>
## Compilation
  For the evaluation your program will be compiled in this way:
  ```bash
  cc -Wall -Wextra -Werror -D BUFFER_SIZE=42 <files>.c.
  ```
  Which will be used as the buffer size for the read calls in your get_next_line. This value will be modified by your evaluators and by the moulinette.
  Your read must use the BUFFER_SIZE defined during compilation to read from a file or from stdin. This value will be modified during the evaluation for testing purposes.
  In the header file get_next_line.h you must have at least the prototype of the function get_next_line.
 
