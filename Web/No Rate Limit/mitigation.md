Define proper rate limiting:  
The appropriate rate and resource limit for each functionality often needs to be different. For instance, the rate limit for authentication endpoints should be much lower to prevent brute-forcing and password guessing attacks. The first thing you can do is to determine what is “normal usage” for that particular functionality. Then, block users whose request resources at a much higher rate than usual.  
In addition, implement limits on payload size to prevent a Denial of Service attack.
