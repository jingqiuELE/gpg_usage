### GPG usage example
gpg  --output hello.gpg --encrypt --recipient alice@gmail.com hello\_gpg.txt
gpg --decrypt hello.gpg

gpg --output hello.sig --clearsign hello\_gpg.txt
gpg --decrypt hello.sig

### Reference
https://www.gnupg.org/gph/en/manual.html#AEN282
