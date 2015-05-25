# Hill Cipher Cracker
A Hill Cipher Cracker that performs automated crib dragging given a known plaintext and a ciphertext.  
*Note*: This script only supports decryption of ciphertexts encrypted with a 3x3 key matrix.  

## Dependencies
This script has to be run with [SageMath(Sage)](http://www.sagemath.org/ "SageMath").

## Usage
1. Clone this repository.
2. Set up the script.
    To specify the ciphertext and the known plaintext, set the `ciphertext` and `KPT` variables, respectively.  

    To specify a custom character set for the Hill Cipher, modify the contents of the `trans_letter_to_num` dictionary. Note that this dictionary must be one-to-one. If your use case is different, you will have to modify the script. The modulo for the Hill Cipher is automatically determined by the length of this dictionary.  
    
3. Run `sage cribdrag.sage`

## Authors
This script was written by [Chesley Tan](https://github.com/ChesleyTan "Chesley Tan") during the HSCTF cybersecurity/hacking competition.
