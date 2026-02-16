**Applying Cryptography in Real-World Scenarios**



**Project Overview**

This project demonstrates the practical application of cryptography using OpenSSL to simulate real-world data protection scenarios.

The focus was on implementing:

    •Symmetric Encryption (AES-256)

    •Hashing (SHA-256)

    •Asymmetric Encryption (RSA)

The goal was to understand how cryptographic techniques ensure confidentiality, integrity, and secure communication.



**Tools Used**

     •OpenSSL

     •Windows Command Prompt

      •SHA-256

      •AES-256-CBC

      •RSA Key Pair Generation



**Symmetric Encryption (AES-256)**

Encrypted and decrypted a plaintext file using AES-256-CBC to demonstrate data confidentiality.

![AES Encryption](Screenshots/aes-decryption.png)




**Hashing (SHA-256)**

Generated hash values before and after modifying a file to demonstrate integrity verification.

![SHA256 Hash](Screenshots/modified-hash.png)





 **Asymmetric Encryption (RSA**)

Generated  public and private keys. The public key was used for encryption and the private key for decryption.


![RSA Keys](Screenshotsrsa-public-keygen 2.png)





 **Challenges Encountered**

    •OpenSSL not recognized as a command (Resolved by adding OpenSSL to system PATH)

    •File path errors during execution (Resolved by proper directory navigation)

     Deprecated rsautl command in OpenSSL 3.x (Switched to pkeyutl)



**Full Documentation**

**Detailed project documentation is available in the attached PDF report.**








