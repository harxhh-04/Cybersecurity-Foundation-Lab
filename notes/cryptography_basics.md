# Cryptography Basics

Cryptography is used to protect data and communication.

## Hashing

Hashing converts data into a fixed-length value.

Common algorithms:
- MD5
- SHA256

Example:
echo "hello" | md5sum
echo "hello" | sha256sum


## Encryption

Encryption converts readable data into unreadable format.

Example using OpenSSL:
openssl enc -aes-256-cbc -in file.txt -out file.enc

To decrypt:
openssl enc -aes-256-cbc -d -in file.enc -out decrypted.txt


## SSL/TLS

SSL and TLS are protocols used to secure internet communication.