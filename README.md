# Hashing-with-a-salt-pepper
Python code to secure sha512 using a salt and pepper. 

# Secure Hashing:
    Hashing is an important feature of cybersecurity. It allows passwords not to be stored 
    in plain-text keeping them safe from hackers. However, many hashing algorithms have been 
    cracked leaving the passwords potentially vulnerable to attackers. This code implements a 
    unique 32 byte salt and a static 34 byte pepper to make the hash value unique and secure.
    
# Usage:
    This project was created in order to farmiliarize myself with hashing and securing it. 
    Feel free to use any aspect of my code and implement it into your own, but I suggest 
    randomly generating a new pepper.
    
 # Next steps:
    In order to make this more secure someone could change the code so that the salt values are not stored
    in the same CSV file as the password hashes so if an attacker gets access to the
    password hash CSV they still do not have any of the salts or the pepper.
