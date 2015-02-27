ClamSMTP TLS
============

ClamSMTP with TLS (STARTTLS) client side support when accepting direct (port 25) connexions.

Originally from http://thewalter.net/stef/software/clamsmtp/ by Stefan Walter.
A git repository was actually here http://thewalter.net/git/cgit.cgi/clamsmtp/ but didn't include the /common/ directory.

Two options have been added to the clamsmtp.conf file:

```conf
TLSKey: /path/to/file.key
TLSCert: /path/to/file.crt
```

Feel free to contact me for any questions or bugs.

