# Caesar-Cipher
Encrypt and decrypt your secret message!

# How to use?
1. Choose between encoding and decoding.
2. Type your message to encode/decode.
3. Type a shift number.
4. Get a encoded/decoded message!

# How it work?
In the list, there are alphabet(lower and capital), numbers(0 ~ 9), and one blank " ".
Each componet has own index and if user input Shift number, program print out shifted message.

Since it has numbers and one blank, almost of sentences are convertable.
Also, if a letter's index exceeds out of range, programm automatically go to beginning index and count rest of shift number.
For exmaple,
list = [A, B, C, D, E]
User's message = "D"
User's shiftnumber = 3
Int this case "D" is converted to "B"
