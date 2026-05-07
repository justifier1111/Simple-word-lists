# An english, number and special charater lists for bruteforcing.

dwyl/english-words list modified for brute forcing by making upper and lower case variants.


AI overview

Hash Type	Speed (GPU)	Time to crack 2.86T combos	Notes

MD5	10-15 B/sec	3-8 hours	Very fast

SHA-1	5-10 B/sec	8-16 hours	Still relatively fast

SHA-256	1-3 B/sec	3-30 days	Moderate speed

SHA-512	500M-1B/sec	3-160 days	Slower than SHA-256

NTLM	10-50 B/sec	2-12 hours	Windows hashes, fast

bcrypt	100k-1M/sec	3-300+ years	Intentionally slow, best practice

scrypt	10k-100k/sec	30-300+ years	Memory-hard, designed for this

Argon2	10k-100k/sec	30-300+ years	Modern, memory-hard

PBKDF2	100k-10M/sec	10-300 days	Depends on iteration count

