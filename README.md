# fundamentals-of-security

You are given a plaintext and a ciphertext, and you know that aes-128-cbc is used to generate the
ciphertext from the plaintext, and you also know that the numbers in the IV are all zeros (not the ASCII
character ‘0’). The key used to encrypt is an English word shorter than 16 characters; the word that can be found from a typical English dictionary. Since the word has less than 16 characters (i.e. 128 bits), space characters (hexadecimal value 0x20) are appended
to the end of the word to form a key of 128 bits. This programs loops over all the words in the provided dictionary file and displays the correct key.
