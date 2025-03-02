<h1>Secure File Encryption Tool</h1>


<h2>Description</h2>
A Python tool that allows users to encrypt and decrypt files using symmetric encryption with the cryptography library. The tool generates a unique encryption key, encrypts the contents of a file, and saves it as a .enc file. Users can also decrypt the encrypted file back to its original content with the provided key. using the Fernet symmetric encryption method from the cryptography library in Python. The tool allows users to securely encrypt sensitive files, turning them into unreadable formats, and later decrypt them back into their original form using a unique encryption key. <br/>
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Cryptography</b>
- <b>PyCharm</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Program walk-through:</h2>

<p align="center">
Start the Encryption Process: <br/>
   In the terminal, the user types python secure_file_encryptor.py to start the program.
<img src="https://i.imgur.com/jCUdqwZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the file name to encrypt:  <br/>
  After running the program, the user is prompted to enter the name of the file they wish to encrypt. 
  The user inputs the file name secret.txt, and the program acknowledges that the file will be encrypted.
<img src="https://i.imgur.com/XSZHa4z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
File encrypted successfully/Enter the file name to decrypt: <br/>
  The program encrypts the file and saves it as secret.txt.enc. 
  Once encryption is complete, the terminal displays a message confirming the encryption was successful.
  The user is then prompted to enter the encrypted file they want to decrypt (e.g., secret.txt.enc).

<img src="https://i.imgur.com/WDKsbW6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
File decrypted sucessfully:  <br/>
The program decrypts the file and restores it to its original state (secret.txt). Displaying confirmation message


<img src="https://i.imgur.com/GqmDQQU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Secret File Content (Before Encryption):  <br/>
The user checks the content of secret.txt, which says "this is a secret message!"
<img src="https://i.imgur.com/MJ4Y7Ep.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Secret File Content (After Encryption):  <br/>
The content of secret.txt.enc is unreadable and appears as an encrypted string like: gAAAAABnxK391e9AXzpc1ohhLYlT0_QGiMegNdEgGcAltHEVWOrzTlkrLiShHc7Y08IVPOmeWtzymsacIgLVNL-pyNa7XitRDD51awms874Wu8YLYl8Vqoo=
<img src="https://i.imgur.com/ehNYRv4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

</p>

