# Security

* Google Cloud Platform - [12 best practices for user account, authorization and password management](https://cloud.google.com/blog/products/gcp/12-best-practices-for-user-account)

>  Do not store plaintext passwords under any circumstances. **Your service should instead store a cryptographically strong hash of the password that cannot be reversed — created with, for example, PBKDF2, Argon2, Scrypt, or Bcrypt.** The hash should be salted with a value unique to that specific login credential. **Do not use deprecated hashing technologies such as MD5, SHA1 and under no circumstances should you use reversible encryption or try to invent your own hashing algorithm.**

## Environment

* [12 factor app](https://12factor.net/)

## Password

* [How to safely store a password](https://codahale.com/how-to-safely-store-a-password/)
* [Everything you ever wanted to know about building a secure password reset feature]()
https://www.troyhunt.com/everything-you-ever-wanted-to-know/
