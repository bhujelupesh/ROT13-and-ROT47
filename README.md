Rot13 and Rot47 Encoder/Decoder Scripts
=====================================

This repository contains two Bash scripts for encoding and decoding strings using the Rot13 and Rot47 ciphers.

**Scripts**

### rot13.sh

This script implements a Rot13 encoder/decoder. Rot13 is a simple character substitution cipher that replaces each letter with the letter 13 positions ahead in the alphabet (wrapping around from 'z' to 'a' and from 'Z' to 'A').

### rot47.sh

This script implements a Rot47 encoder/decoder. Rot47 is a simple character substitution cipher that replaces each character with the character 47 positions ahead in the ASCII table (wrapping around from '!' to '~' and back to '!').

**Usage**

To use either script, simply run it in your terminal and follow the prompts:

1. Enter the string you want to encode or decode.
2. Choose whether to encode (0) or decode (1).

The script will then output the encoded or decoded string.


**License**

This script is open source

**Contributing**

If you'd like to contribute to this repository, please fork it and submit a pull request. I'd love to hear your suggestions or improvements!

**Author**

Upesh Bhujel

Feel free to customize this `README.md` file to fit your needs. Make sure to update the `Author` section with your own name. Good luck with your GitHub repository!

**Example**
### Rot13 Encoding

```bash
$ ./rot.sh
Choose a cipher:
 Rot13(0) or Rot47(1) 
0
Enter your string here: Hello World
What do you want to do?
 Encode(0) or Decode(1) 
0
Rot 13 encoded string: Uryyb Jbeyq

-----For ROT47-------
$ ./rot.sh
Choose a cipher:
 Rot13(0) or Rot47(1) 
1
Enter your string here: Hello World
What do you want to do?
 Encode(0) or Decode(1) 
0
Rot 47 encoded string: pFS:]i~Fzq



