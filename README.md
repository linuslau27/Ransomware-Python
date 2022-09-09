# Ransomware-Python

Summary:
This is a Ransomware script which encrypts files in a local directory and prompts for secret phrase to decrypt

To use:
-create a .TXT file in the same dirrectory as these two scripts 
-run the Ransomware.py script 
-check to see that contents of your .TXT file have been encrypted 
-run the decrypt.py script and enter the passphrase (defined in the same decrypt.py script)

Special notes:
-Make sure you do not run Ransomware.py more than once, otherwise a different key will be generated and the text file will be undecryptable 
-If you accidentaly do this, you can just delete all files except for Ransomware.py and decrypt.py and restart the process. 
-You may need to install/update python3 as well as the Fernet module. 
