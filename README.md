# Enigma
A Encoder Decoder program in Python using Tkinter and base64 modules of it.

Historically, The Enigma machine was a cipher device developed and used in the early- to mid-20th century to protect commercial, diplomatic, and military communication. It was successfully deciphered by the famous British Matematician Alan Turing, who is now a highly revered figure in Computation and Mathematics.

# Working
My Enigma program, internally, works on base64 module of Python. Base64 has functionalities to convert ASCII characters into binary and binary characters back to ASCII.

An interactive UI is also designed with tkinter. 

![image](https://user-images.githubusercontent.com/72162628/172051102-998b7b8d-2b02-498b-8b56-fcfa4041d588.png)

We can enter any **Message** and a **Key**, which is to be kept secret.

During Encoding, we enter 'e' as **Mode** and then press **Result** button to get encrypted message.

This encrypted message can be shared with anyone and the other party can decode it by entering the encrypted message as Message

with the same key and 'd' to signify decoding.

The end Result will be the same message, entered by the user.

**Reset** button can be used to reset all fields to empty.

**Exit** button terminates the program.


# Output

![image](https://user-images.githubusercontent.com/72162628/172051196-44490fe9-f799-451f-988b-302e4bb35760.png)

# Its Uses
This application can be used in secure encryption-decryption of messages which can be used to transfer message confidentially.
