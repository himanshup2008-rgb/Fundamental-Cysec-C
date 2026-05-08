# Fundamental-Cysec-C
I realized I was lacking in C so I decided to learn it.

The zip includes a Master project executable which contains 4 tools. 

1. Caesar Cipher which uses number as an input to shift alphabets forward or backward to encrypt or decrypt respectively. Has been optimized and can use large keys. However it only works on alphabets. 

2. Password Checker which you guessed it checks password strength using the parameters coded.

3.Hex Dumper. This one might be a bit confusing since the location is hard coded but it extracts text from a file and dumps its hexadecimals. There is a HexTest.txt to test it but if you want to use your own files you can change its code in HexDump.c in the src folder.

4.XOR encrypter is an encrypter like Caesar Cipher but it uses a ^ operator alongside the alphabet key to Xor the text and encrypt it into hexadecimals, try using it on you name and turn it into 0A or whatever. For this you are going to need to enter the key in alphabets, use only a single letter. There is a decrypt function to that uses the same key to turn your name back. Enter the hexadecimals with or without spaces when decrypting it has been optimized.

Let me know of any errors or bugs, I like learning... thank you.
