# Writeup 3 - Operational Security and Social Engineering

Name: Chase Wooten
Section: 0101

I pledge on my honor that I have not given or received any unauthorized assistance on this assignment or examniation.

Digital acknowledgement: Chase Wooten

## Assignment Writeup

### Part 1 (40 pts)

If I had to find this information through social engineering I would probably pose as someone from the wherever Elizabeth's banks. I would guide her to a malicious website but preface it with a question about her browser. To get what her browser she uses I would say something about if shes using a certain browser such as google chrome since she would likely be using that or another popular browser she might have trouble seeing some of the information if flash isnt enabled or something along the lines of that. Once on the website she would have to log into her bank account using her id and pin and it would alert her to answer security questions because it was "the first time this device logged onto the account". From this I would get her to enter her mothers maiden name, her city of birth, and the name of her first pet. I would probably get a keylogger onto her computer during this step as well. 

### Part 2 (60 pts)

The first vulnerability I would suggest would be to up the complexity requirements of passwords for the website. Her password was found inside of a wordlist document so it had to be a very common guessable password. Having tougher password requirements would elminate this vulnerability. I would also suggest not allowing logins to the same account be repeatable more than some low constant number of times, this would elminate the chance of brute forcing a password to gain access to an account. The last thing I would suggest is to make the webservice that handles logging into the website only available to certain people by having it behind an ssh tunnel so the port could not be accessed outside of the box. This would prevent the possibility of outside attacker to make use of the port.

https://security.stackexchange.com/questions/153206/exposing-ports-or-hide-them-behind-proxy
