# Passwords
Create a random password generator and then use various methods to crack it.  

## Random Password Generator
Create a Python program that generates a password of random letters and characters. Include lowercase, uppercase and digits and optionally, puncutation.  

Instead of intializing a string or list that contains them, python has library `string` that can be imported.  Some of the functions that `string` includes is:

`string.ascii_letters`: The concatenation of the ascii_lowercase and ascii_uppercase constants.  
`string.ascii_lowercase:` All lowercase letters
`string.digits`: '0123456789'  
`string.puncuation`: all characters considered to be puncuation.  

```
import string

letters = string.ascii_lowercase

```

## Directions:
- Create a function `generate` that has parameter of length that determines the length of the password. 
- Your function should include all letters and digits (optionally include punctuation)
- It should randomly pick from available characters. 
- Call `generate` and test your outputs.  
- Test `generate` by prompting for user input


## Next Class:
We will use generate passwords and see how long they take to be brute-forced by various password - crackers 





