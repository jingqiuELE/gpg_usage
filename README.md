### GPG usage example
  * Encrypt a document
```
gpg  --output hello.gpg --encrypt --recipient alice@gmail.com hello_gpg.txt
gpg --decrypt hello.gpg
```

  * Clear sign a document
```
gpg --output hello.sig --clearsign hello_gpg.txt
gpg --decrypt hello.sig
```

### Reference
https://www.gnupg.org/gph/en/manual.html#AEN282
