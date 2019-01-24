# Mastering_arrays
Create a class called <b>Text</b> which is going to represent a text. Objects of type text are going to be instantiated by specifying a set of characters (char). As attribute, this class is going to have an array of characters. If necessary, other attributes can be created.  
Objects Text methods are: 
<ul>
    <li><b>public Text(char[] characters)</b></li>
    <li><b>public int countChars(char c)</b>: count the number of ‘c’ within the text.</li>
    <li><b>public int indexOf(String occurrence)</b>: gives the position within the text in which the EXACT “occurrence” (minding cases) has been firstly found. Example: 
    <ul>
    <li>Text = “today is such a nice day. I like nice days”</li>
    <li>Occurrence = “nice” </li>
    <li>Expected result = 16. Mind spaces and that the second nice has been discarded.</li>
    </ul></li>
    <li><b>public boolean isPalindrome()</b>: a word or group of words that is the same when you read it forwards from the beginning or backwards from the end. Example: “Refer” and “Level” are palindromes.</li>
    <li><b>public int countOccurrence(String occurrence)</b>: counts the number of “occurrence” within text. Search must be case insensitive. Example: 
    <ul>
        <li>Text = “Love is all over the place. Spread love!” </li>
        <li>Occurrence = “love”</li>
        <li>Expected result = 2</li>
    </ul></li>
    <li><b>public int countWords(int wordLength)</b>: counts the words that have a length greater than wordLength. </li>
</ul> 