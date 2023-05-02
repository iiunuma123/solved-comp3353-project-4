Download Link: https://assignmentchef.com/product/solved-comp3353-project-4
<br>



<ul>

 <li>Defining and accessing Arrays.</li>

 <li>Dealing with Registers and instructions.</li>

 <li>Defining with Loops Debugging and running your assembly code.</li>

</ul>

<strong><em>Requirements: </em></strong>

<ul>

 <li>Read the design section and write a program. Submit source file .asm to Canvas.</li>

 <li>Please start early. ZERO point for late submission. You cannot submit your assignment after 11:59pm on the due day.</li>

</ul>

<strong><em>Deliverables: </em></strong>

<ul>

 <li>Save your source of assembly program as a .asm document.</li>

 <li>Name document as a “Firstname_Lastname.asm”.</li>

 <li>(5 points) Please provide a heading at the top of your code containing your name, Auburn UserID, filename, and how to compile your code just as project 3 required.</li>

 <li>(5 points) Source file can be compiled successfully and no run-time error.</li>

 <li>Submit your “Firstname_Lastname.asm” through the Canvas system. You do not need to submit hard copies.</li>

</ul>

<strong><em>Rebuttal period: </em></strong>

<ul>

 <li>You will be given a period of 3 business days to read and respond to the comments and grades of your homework or project assignment. The TA may use this opportunity to address any concern and question you have. The TA also may ask for additional information from you regarding your homework or project.</li>

</ul>




<strong><em>Design: </em></strong>

The objective of this assignment is to create a program that will determine if two strings are anagrams. If the two strings are anagrams, then EAX will have the value 1 after the code has completed. If they are not anagrams, then EAX will have the value 0.

Two .java implementations are in the “files” section in Canvas. Feel free to use one of these or another method.

All “high level” directives are not allowed on this homework. (e.g. IF, ENDIF, REPEAT, etc.)




What is anagram? From dictionary.com:




<h1>an·a·gram</h1>




/ˈanəˌɡram/




<em>noun </em>




noun: <sub>  </sub><strong>anagram</strong>; plural noun: <strong>anagrams </strong>

a word, phrase, or name formed by rearranging the letters of another, such as cinema, formed from iceman.




You can read more about in Wikipedia: https://en.wikipedia.org/wiki/Anagram




<strong>Design: </strong>




Create a BYTE array with the label ‘s1’. This array may be of any length between 2 and 100.




Create a BYTE array with the label ‘s2’. This array should be the same length as ‘s1’.




You may create any other values you deem necessary.




The program should compare the two strings to determine if they are anagrams.




Assume that each of the arrays (s1 and s2) will be the same length. Also assume that all characters in the array will be capital letters.




Program:




Your job is to implement a MASM version of the java program ‘AnagramCounter.java’ or ‘AnagramReplace.java’, or with your own reasonable method.




(90 points) 9 lines to implement commented with numbers from (1) to (9). See template for details.




Example:




s1 BYTE               “GARDEN” s2 BYTE “DANGER”

After the code completes EAX would have the value 1. (These are anagrams)




Another example: s1 BYTE “CODE” s2 BYTE  “DOGS”

After the code completes EAX would have the value 0. (These are not anagrams)




Remember that your program must be flexible enough to handle a string of any length. I could test with a string of length 2 or 100 or any number in between.