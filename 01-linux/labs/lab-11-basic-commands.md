
# Lab: Bandit Level 11 → 12

## Objective
Decode a ROT13 encoded file to retrieve the password.

## Commands Used
`cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'`

## Output
bandit11@bandit:~$ cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
The password is 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4

## Challenges
I had to understand how ROT13 mapping works and how tr transforms characters.

## What I Learned
- ROT13 shifts letters by 13 positions in the alphabet
- `tr` maps characters from one set to another
- ROT13 is reversible by applying the same transformation again`


