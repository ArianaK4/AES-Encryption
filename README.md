<h3 align="center"> This is the implementation for AES128 encryption</h3>
<h4>The message that will be encrypted is in the main() function with the text: "This is a message we will encrypt with AES!"</h4>
<h4>The first function that will be called is AES_Encrypt() which takes for parameters the message and the key. For AES128 there are 10 rounds where four different
functions are called: 
<br></br>
         <br>1. subBytes()</br>
         <br>2. shiftRows()</br>
         <br>3. mixColumns()</br>
         <br>4. addRoundKey()</br></h4>
<h4>Before we loop through the rounds an addRoundKey() is called first and then we loop through 9 rounds. For the last round there is a difference where all
the functions are called except for mixColumns() function.</h4>
<h4>After AES_Encrypt() function we print the encrypted message through the printHext() function.</h4>

<h4>The result of the encrypted message for this example will be: B6 4B 27 BB 16 15 A6 F5 32 18 6C C5 FA 94 B5 5E 5C 54 EA 1B DF 97 1E 3D E3 1B FC 02 75 22 76 52 D5 7B D5 42 BA 
0F 68 50 CD FD 59 B8 EB 0E 83 D1</h4>
