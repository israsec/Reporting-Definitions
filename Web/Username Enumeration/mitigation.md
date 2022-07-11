Avoiding user enumeration is a matter of making sure no pages or APIs can be used to differentiate between a valid and invalid username, unless the matching password is supplied. The exact mitigation depends on the location of the input parameter. 

Login:  
Make sure to return a generic “No such username or password” message when a login failure occurs.  
Make sure the HTTP response, and the time taken to respond are no different when a username does not exist, and an incorrect password is entered.  

Password Reset:  
Make sure your “forgotten password” page does not reveal usernames.
If your password reset process involves sending an email, always return a generic message such as "An email has been sent to the provided email."

Additionally, it is always recommended to implement a CAPTCHA or similar mechanism to prevent mass username enumeration.
