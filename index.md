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
* ``grep -i Example jouranl.pbio.0020001.txt``
* Output:
![Image](https://github.com/vesalcido/cse-15l-lab-report3/blob/main/Screen%20Shot%202023-05-10%20at%205.25.05%20PM.png)
* ``grep -i`` seems to return instances where that certain word is found regardless of what case my input is in. Essentially its ignoring the uppercase and still finding the word in the body of text.
* Example 2:
* Input:
* ``grep -i unesco journal.pbio.0020001.txt``
* Output:
![Image](https://github.com/vesalcido/cse-15l-lab-report3/blob/main/Screen%20Shot%202023-05-10%20at%205.34.24%20PM.png)
* ``grep -i`` continues to show that regardless of the case that the user inputs, it'll still return the word your looking for in its original form, within the phrases and sentences of the text. This could be seen as important due to a case where you need to find a certain word and can type it in without it being case sensitive.

**``-v``**
* The first example that I did was using ``-v`` on the ``./technical`` file ``plos`` to be able to see the behavior or the action that ``-v`` would have on the file.
* Input:
* ``grep -v UNESCO journal.pbio.0020001.txt``
* Output:
![Image](https://github.com/vesalcido/cse-15l-lab-report3/blob/main/Screen%20Shot%202023-05-10%20at%205.47.45%20PM.png)
* ``grep -v`` seems to return lots of sentences and paragraphs that don't contain the word that I originally inputed. So, lots of the origianl text is returned but without certain sentences.
* Example 2:
* Input:
* ``grep -v 2 journal.pbio.0020001.txt`` 
* Outpt:
![Image](https://github.com/vesalcido/cse-15l-lab-report3/blob/main/Screen%20Shot%202023-05-10%20at%206.01.31%20PM.png)
* ``grep -v`` continues to show that regardless of a phrase or number input, the output would still be large body of the text without the actual input found within the text. This could be seen as important due to a case where a user would want to exclude phrases with certain words or numbers, in which they could use this command to get rid of the unwanted phrases.

**``-c``**
* The first example that I did was using ``-c`` on the ``./technical`` file ``plos`` to be able to see the behavior or the action that ``-c`` would have on the file.
* Input:
* ``grep -c rather journal.pbio.0020001.txt``
* Output:
![Image](https://github.com/vesalcido/cse-15l-lab-report3/blob/main/Screen%20Shot%202023-05-10%20at%206.21.44%20PM.png)
* ``grep -c`` seems to return a number to indicate how many times the word inputed shows up in the body of text.
* Example 2:
* Input:
* ``grep -c 10% journal.pbio.0020001.txt``
* Output:
![Image](

    
