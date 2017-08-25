# securitools

## genpass
Hash your plain text password to become a strong hexadecimal one and then use it.
```

MBP:~ hussein$ genpass 
Enter the password 👀
Mjg2NzU1ZmFkMDQ4NjljYTUyMzMyMGFjY2UwZGM2YTQgIC0K
Copy it and clear the console 🙄
```

## crypto
Encrypt and decrypt files in a very simple way.

```
⚠️  Usage: crypto [-e file_to_encrypt | -d file_to_decrypt]
```

```
MBP:~ hussein$ crypto -e secret_file.zip 
🔒  Encrypting secret_file.zip using AES with 256 bit key length in CBC mode
enter aes-256-cbc encryption password:
Verifying - enter aes-256-cbc encryption password:
✅  secret_file.zip is encrypted as secret_file.zip.enc

MBP:~ hussein$ crypto -d secret_file.zip.enc 
🔓  Decrypting secret_file.zip.enc using AES with 256 bit key length in CBC mode
enter aes-256-cbc decryption password:
✅  secret_file.zip.enc is decrypted as secret_file.zip
```
