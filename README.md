# deal-screener-data

The daily deal-screener dashboard, password-locked (AES-256-GCM, key derived from the password
with PBKDF2-SHA256, 600,000 rounds). The page decrypts in your browser; nothing here is readable
without the password.

This repository holds only that one page. No code, passwords or API keys live here. It is
replaced, not appended to, after every run (single commit, force-pushed).
