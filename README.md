# xenoverse2_ps4_decrypt
Tool to decrypt and encrypt DRAGON BALL XENOVERSE 2 saves from the PS4 (mounted save)

# Requriements
pycryptodome needs to be installed using the following command
```
pip install pycryptodome
```
## Usage
```
usage: why.py [-h] [-e] input_file output_file

Tool to decrypt and encrypt DRAGON BALL XENOVERSE 2 saves from the PS4 (mounted save)
positional arguments:
  input_file    XENOVERSE 2 save (eg SDATA000.DAT) to decrypt/encrypt
  output_file   Output file path of encrypted/decrypted save (eg SDATA000.DAT.dec)

options:
  -h, --help    show this help message and exit
  -e, --encode  Encrypt the save, otherwise decrypt it
```
## Example command to decrypt a save
```
python xenoverse2_ps4_decrypt.py SDATA000.DAT SDATA000.DAT.dec
```
## Example command to encrypt a save
```
python xenoverse2_ps4_decrypt.py SDATA000.DAT.dec SDATA000.DAT -e
```
