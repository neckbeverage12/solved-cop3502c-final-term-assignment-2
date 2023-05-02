Download Link: https://assignmentchef.com/product/solved-cop3502c-final-term-assignment-2
<br>
<strong>Introduction: </strong>For this assignment you have to write a c program that will utilize the Binary Search Tree (BST).




<strong>What should you submit? </strong>

Write all the code in a single file and upload the .c file.




Please include the following lines in the beginning of your code. By writing this line you also agree that you have written the code:




/* COP 3502C Final term Assignment 2

This program is written by: Your Full Name */




<strong>Compliance with Rules:</strong> UCF Golden rules apply towards this assignment and submission. Assignment rules mentioned in the syllabus, are also applied in this submission.




Do not post or share part or full solution of your assignment anywhere!

<strong> </strong>

<strong>Additional notes: </strong>The TAs and course instructor can call any students to explain their code for grading.

<strong> </strong>

<h2>Problem</h2>

In this assignment, you have to read a text file (in.txt) that contains a set of words. The first line of the file contains 3 numbers <strong><u>(N, S, D).</u></strong> These numbers represent the sequence of input words in your file.

<strong><u>N:</u></strong>  represents the number of words to read to build binary search tree. You have to write a recursive insert code to create and insert these words into the binary search tree. After inserting all the items, you should show the words in Pre order, In order, and Post order. So, you need to create three functions for this purpose.

<strong><u>S:</u></strong> represents the number of the words to search from the tree. These S words are placed after the first N words in the input file.You need to implement a search function that will be able to search these words in your BST.

Additionally, the search words will also be used to look in the binary search tree and count number of words in the tree that come before the search word, alphabetically. You will need to create a recursive function with the following prototype <strong><em><u>CountBefore(treeNode* root, char</u> <u>searchKey</u></em><u>[])</u>, </strong>where treeNode is the node structure of your tree.

<strong><u>D:</u></strong> represents the number of words to be deleted from the BST. This list of words are placed after N+S words in the input file. Write a recursive delete function for your task. After deleting all the items, also show the tree in only in-order traversal.

<strong>Other required functions:</strong> In addition to the general functions for the above tasks, your code should also contain the following functions.

<strong><u>totalCharacters(<em>treeNode* root</em>):</u></strong> This function takes the root of the tree in parameter and returns the total number of characters in the whole Binary Search Tree. You need to call this function after creating the tree and also at the end of deleting the requested nodes from the tree.

<strong><u>isBalanced(<em>treeNode* root</em>):</u></strong> We call the tree as imbalanced if the differences between the height of left subtree and height of right subtree is more than one. This function takes the root of the tree in parameter and returns 1 if the tree is balanced, otherwise it returns 0. In this process,  you might consider implementing a height function to get the height of a subtree. The isBalanced function should be called after creating the tree and also at the end of deleting the requested nodes from the tree.




<strong>Example: </strong>

The figure below shows an example of BST with strings.







All the output must be written to the out.txt file according the sample output shown bellow.  You may output in the console, however, we will mainly see the out.txt file for our given input file.Do not hardcode your code only for the example provided below. If we see you have hardcoded any output, you will get zero for your full assignment submission.













<strong>Example </strong><strong>ample Input file in.txt:  </strong>

<strong>            </strong>9 3 4 judy         mary bill       alice tom         fred jane

<sup>           </sup>joe

dave




jane      jones judy              alice mary

judy fred




<strong>Sample Output file out.txt:  </strong>

<table width="612">

 <tbody>

  <tr>

   <td width="612">Pre Order: judy bill alice fred dave jane joe mary tomIn Order: alice bill dave fred jane joe judy mary tomPost Order: alice dave joe jane fred bill tom mary judyTotal characters: 35Height left= 3, height right = 1. The tree is imbalanced!Search Phase: jane: Found, Items before: 4  jones: Not found, Items before: 0 judy: Found, Items before: 6  Delete Phase: alice: deleted mary: deleted judy: deleted fred: deletedIn Order: bill dave jane joe tom</td>

  </tr>

 </tbody>

</table>

<strong>Requirement: </strong>

You must use file IO, Binary Search Tree and relevant traversal for your solution. All the information must be extracted from the tree.

Your program must have to compile in EUSTIS to get credit.