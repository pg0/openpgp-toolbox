# Encryption Toolbox

## Tools
### Synchonous Encryption
* AES256 (PBKDF2)
* AES-EAX

### Asynchonous Encryption
* Public-Key Encryption
  Multiple Receipients possible

You can find an >> <a href="https://patrickgawron.com/encrypt/">online version here</a>

### UseCase:
* **contact form on your website**

Public-Key Cryptography in the browser

A visitor can send you a message which gets encrypted on the client side, 
then submitted via mail to you
auto-decrypted via enigmail or similar
* **encrypt/decrypt messages without the need for gpg software**
* **generate key-pairs offline**

### Key Generation
You can select between
* RSA4096
* ECC EdSA386

**PublicKeys are not uploaded!**\
You have to share them yourself\
or upload them manually

### Dependencies:
- OpenPGP implementation for JavaScript https://openpgpjs.org
- JQuery https://jquery.com (not necessarily)
