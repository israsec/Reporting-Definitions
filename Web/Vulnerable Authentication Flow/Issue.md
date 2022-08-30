This vulnerability is a result of several lesser vulnerabilities chained together into an exploit chain with a highlevel of risk.

1) Username enumeration – allows an attacker to validate existing users on the website.

2) No Rate Limiting – allows an attackerto enumerate at scale. Instead of entering usernames one at a time, we are able to brute force all potential usernames to compile a list of ALL valid users.

3) Weak Password Policy – because the passwords are not very complex the chances that one of the enumerated user’s has a password like password123or Aa123456 is very likely.

Together  this  exploit  chain may allow an  attacker  to  compromise  multiple  users  of  the  web application through a password spray or brute force attack.
