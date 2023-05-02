Download Link: https://assignmentchef.com/product/solved-coen79-lab-5-string-class
<br>
You will complete the implementation for <strong>a version of the Standard Library’s string class</strong>. Please download and read through this header file: mystring.h




You are to write the implementation for the above header file in a file named mystring.cpp. Please note that the name of the actual class that you are writing is string, not mystring. For this reason, the use of namespaces is particularly important to this lab, as your class will have the same name as that of the Standard Library’s string class.




You are allowed to use functions from the library &lt;cstring&gt; to assist you in writing your functions for things like copying between strings or appending strings to one another. You are to make sure, however, that you use safe versions of these strings. For example, you should use strncpy and strncat, not their less secure alternatives of strcpy and strcat. Finally, you may NOT use the “strdup” function.




Some of the important functions to be implemented are:

<ul>

 <li>A new constructor that has one parameter (a character). The constructor initializes the string to have just this one character.</li>

 <li>An insertion function that allows you to insert a string at a given position in another string.</li>

 <li>A deletion function that allows you to delete a portion of a string.</li>

 <li>A replacement function that allows you to replace a single character in a string with a new character.</li>

 <li>A replacement function that allows you to replace a portion of a string with another string.</li>

 <li>A search function that searches a string for the first occurrence of a specified character.</li>

 <li>A search function that counts the number of occurrences of a specified character in a</li>

</ul>

string.

<ul>

 <li>A more complex search function that searches through a string for an occurrence of some smaller string.</li>

</ul>