# The-Imitation-Game
You are a mathematician during world war 2, who has joined the cryptography team to decipher the enemy's enigma code. Your job is to create a program to crack the codes.  

On the first line of the input you will receive the encrypted message. After that, until the "Decode" command is given, you will be receiving strings with instructions for different operations that need to be performed upon the concealed message to interpret it and reveal its true content. There are several types of instructions, split by '|' 

Move {number of letters} 

Moves the first n letters to the back of the string.  

Insert {index} {value} 

Inserts the given value before the given index in the string. 

ChangeAll {substring} {replacement}  

Changes all occurrences of the given substring with the replacement text. 
