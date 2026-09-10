# ai-industry-whitehall

A password-protected static page. `index.html` is AES-256-GCM ciphertext with a
PBKDF2-SHA256 key; it decrypts in the browser once the passphrase is entered.
Nothing readable is stored in this repository.
