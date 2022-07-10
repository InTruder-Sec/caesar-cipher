# Caesar-cipher
The Caesar Cipher technique is one of the earliest and simplest methods of encryption technique. It’s simply a type of substitution cipher, i.e., each letter of a given text is replaced by a letter with a fixed number of positions down the alphabet. For example with a shift of 1, A would be replaced by B, B would become C, and so on. The method is apparently named after Julius Caesar, who apparently used it to communicate with his officials. 

Thus to cipher a given text we need an integer value, known as a shift which indicates the number of positions each letter of the text has been moved down. 
The encryption can be represented using modular arithmetic by first transforming the letters into numbers, according to the scheme, A = 0, B = 1,…, Z = 25.

This tool allows you to encrypt any string into cipher text. Moreover it also allows you to decode all the posibilites of the cipher text.

# Usage

**The tool is easy to use, for installation of the tool follow the bellow commands,**
```
git clone https://github.com/InTruder-Sec/caesar-cipher
```

**For the encryption of a cipher text:**
``` 
python ccd.py
1
{ENTER YOUR TEXT HERE}
{ENTER NUMBER OF CHARACHTERS YOU WANT TO SHIFT}
```

**To decrypt any cipher text:**
```
python ccd.py
2
{Enter your cipher text here}
```
