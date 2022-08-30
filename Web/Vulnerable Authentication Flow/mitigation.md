Fix all the underlying vulnerabilities that may lead to exploitation of this vulnerability. 

This includes:

1. Fixing username enumeration by providing a generic response to failed login and password reset attempts. The generic response is something like “Wrong Username and/or Password” and for password reset pages, display a message like “An message has been sent to the email on record”, regardless of whether the email exists or not.

2. Fixing API Rate Limiting by implementing a rate limitation. This can based on the attacker IP and can be set to block the IP for a certain amount of time after a certain threshold has been reached. This will prevent the A) the enumeration of valid users and B) spraying one password against many valid users. 

3. Increase Password complexity requirements. Require the use of special characters and a mix of lowercase and uppercase letters along with numbers
