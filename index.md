# Lab Report 3
## Interesting Command Line Options for Grep
* ``-e`` pattern
* ``-i`` ignore uppercase and lowercase
* ``-v`` invert match
* ``-c`` output count of matching lines only
## Examples of Each
**``-e``**
* The first example that I did was using ``grep -e`` on the ``./techincal`` file ``plos`` to be able to see the behavior or the action that ``-e``
would have on the file.
* Input:
* ``grep -e science journal.pbio.0020001.txt``
* Output:
 ![Image](https://github.com/vesalcido/cse-15l-lab-report3/blob/main/Screen%20Shot%202023-05-09%20at%2010.20.23%20PM.png)
* It seems that ``grep -e`` returns lots of sentences that contain the word ``science``. This command could be seen as useful to find a certain word or phrase within a huge body of text.
* Example 2:
* Input:
* ``grep -e 2003 journal.pbio.0020001.txt``
* Output:
![Image](https://github.com/vesalcido/cse-15l-lab-report3/blob/main/Screen%20Shot%202023-05-09%20at%2010.31.10%20PM.png)
* ``grep -e`` continues to show that not only is it able to take in words to find a pattern, but can take in numbers and output lines with that exact numbers. This could also be seen as important if there is a case to find a certain number within a large body of text.

**``-i``**
* The first example that I did was using ``-i`` on the ``./technical`` file ``plos`` to be able to see the behavior or the action that ``-i`` would have on the file.
* Input:
* ``grep -i

    
