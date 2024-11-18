- Characterize the difference between a database hack and a database leak.

The database hack is linked to an attack and the database leak is due to human error like accidentally exposes sensitive data.

- In what sense might files not actually be deleted even if you empty the recycle bin on Windows or empty the trash on macOS?

The system don't real remove the data, he forget where the file is and the file continue existing until get reused by other file.

- How do quantum computers differ from traditional (non-quantum) computers?

Traditional computer systems works with bits, 0 or 1, representing one state at once. Quantum computers uses a quantum bit or qubit, which can represent 0 and 1 at same time, representing two states at once. So quantum have exponentially more computing capabilities.

- What is the term for the prevailing method via which public-key (i.e., asymmetric) cryptography enables two parties to establish a shared secret, even over an insecure (i.e., unencrypted) channel?
Asymmetric key cryptography

Asymmetric key cryptography

- What is a salt, in the context of this lecture?

Is a value added to the hash function to change the hash. The values ​​provided, even if equal, will have a different hash.

- Suppose that you have been hired to perform some work for Charlie. After agreeing to terms, you send the contract to Charlie via email, and, later that day, you receive a digitally signed copy from an email address that appears to belong to Charlie but isn't the one to which you sent the contract originally.

- How can you be as certain as possible, technologically (that is, without consulting Charlie) that Charlie was the one who digitally signed the contract?

Verify the signature with the public key and compare if the hashes values match.

- MD5 is an example of a still popular hashing algorithm that has been in use since the early 1990s. Read this article (https://www.okta.com/identity-101/md5/) about MD5 before continuing on.

Note that MD5 is a 128-bit algorithm, meaning its digests (i.e. hash values) are always 128 bits in length, and therefore there are 2^128 unique digests available. Thus, understand that the article's critique that there is a "high potential for collisions," while not invalid or indeed even incorrect, is perhaps something that should be understood with a bit of context.

Suppose that a company has made a large file available for download via its website. Why might they also make available the MD5 hash of that file (as is indeed a common practice)?

To verify file integrity, checking and ensure that the file is not accidentally corrupted.

- Identify one or more significant differences between a cipher and a hash.

Cipher is for encryption and decryption, transform plaintext into ciphertext and vice-versa.
Hash convert plain text into a hash value. Without access to the hash function, the hashed value cannot be reversed.

- Otkz D zvmizy v amzz kjdio! di ocz wjs wzgjr.
No, the above isn't random typing! :)

I earned a free point!
