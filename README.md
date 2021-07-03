# Fibonacci-Heap-in-C

## Question

Write a program to implement a Fibonacci Heap H and perform the operations insertion, deletion, extract minimum, decrease key and union. Your program should contain the following.<br>


functions:
<li> MakeHeap() - Creates and returns a new heap H containing no elements.
<li> Insert(H, x) – Inserts a new node with key ‘x’ into the heap H.
<li> Minimum(H) – Returns a pointer to the node in heap H whose key is minimum.
<li>  ExtractMin(H) – Deletes the node with minimum key value from heap H.
<li> DecreaseKey(H, x, k) – Decreases the value of node ’x’ of the heap H by ’k’, if node x’s
key is at least ’k’. Otherwise, it returns NIL.
<li> Delete(H, x) - Deletes the node with key ’x’ from the heap H. (If node is not present, it
returns NIL)
Input Format:
<li> Each line contains a character ‘i’, ‘m’, ‘x’, ‘r’, ‘d’ or ‘e’ followed by at most one integer. The
integers, if given, are in the range [−106
, 106
].
<li> Character ‘i’ is followed by an integer separated by space; a node with this integer as key is
created and inserted into H.
<li>  Character ‘m’ is to print the node with minimum key value from H.
<li>  Character ‘x’ is to delete the node with minimum key value from the heap H and the deleted
node’s key is printed.
<li>  Character ‘r’ is followed by two integers separated by a space; a node with the first integer as
key is searched and its key value is decreased by the second integer and the updated node’s
key is printed.
<li>  Character ‘d’ is followed by an integer separated by space; the node with this integer as key
is deleted from H and the deleted node’s key is printed.
<li> Character ‘p’ is to print the heap H in which each nodes are separated by a space.
<li>  Character ‘e’ is to ‘exit’ from the program.
  
  
Output Format:
<li> The output (if any) of each command should be printed on a separate line.


<br><br>


<br>
Sample Input:<br>
i 10<br>
i 20<br>
i 30<br>
i 40<br>
i 50<br>
m<br>
x<br>
p<br>
r 50 15<br>
p<br>
e<br>

Sample Output:<br>
10<br>
10<br>
20 30 40 50<br>
35<br>
20 30 40 35<br>
