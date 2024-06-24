# Caesar cipher

This repo contains scripts to play around with the ceasar cipher. 

## caesar-cipher.py
```
This is a simple tool to cipher/decipher messages with the ceasar cipher method

usage: ceasar-cipher.py [-h] [-o OUTPUT] {cipher,decipher} shift textfile
ceasar-cipher.py: error: the following arguments are required: mode, shift, textfile
```

## crack-the-caesar.py
```
This is a simple tool to crack a message encrypted with the caesar cipher method.

usage: crack-the-ceasar.py [-h] [-o OUTPUT] textfile
crack-the-ceasar.py: error: the following arguments are required: textfile
```

## Examples:

```
python3 caesar-cipher.py cipher 5 ASCII.txt -o ASCII.txt.ciphered
```

Cipher the contents of ```ASCII.txt``` to the file ```ASCII.txt.ciphered``` (see sample file).

```
python3 crack-the-caesar.py secret.txt -o output.txt
```

Try all 26 combinations on the ```secret.txt``` file and write to ```output.txt``` (see sample file).
