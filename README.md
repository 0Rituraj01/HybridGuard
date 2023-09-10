<p align = "center">
<img src = "images/Hybrid Encryption.png">
</p>

# HybridGuard

The primary objective of this initiative is to enhance file security through the utilization of hybrid encryption methods while safeguarding the data within our local system.

Hybrid encryption encompasses the utilization of both the RSA Encryption Algorithm and the AES Encryption Algorithm to fortify data protection.

# Here's how it operates:

* Key Generation: The project begins by creating directories and files to generate RSA and AES keys. These keys are essential for the encryption and decryption processes.

* Encryption Process: When encrypting a file, the project first retrieves the AES key from its corresponding file. It then decrypts this AES key using the RSA private key. With the decrypted AES key, the selected file is encrypted using the AES encryption method. The resulting encrypted file is securely stored within the local system.

* Decryption Process: To decrypt a file, the project follows a similar procedure. It starts by acquiring the AES key file and decrypting it using the RSA private key. Once the AES key is obtained, it is used to decrypt the selected file, which is then stored in its original form within the local system.

This approach combines the strengths of RSA and AES encryption, providing a robust security solution for file storage and transmission within the local environment.


## Requirements 
* You must be install the Crypto package using bellow command in terminal.

    `pip install pycryptodome==3.9.9`

