# Writeup 2 - OSINT

Name: *PUT YOUR NAME HERE*
Section: *PUT YOUR SECTION NUMBER HERE*

I pledge on my honor that I have not given or received any unauthorized assistance on this assignment or examniation.

Digital acknowledgement: *PUT YOUR NAME HERE*

## Assignment Writeup

### Part 1

In class you were given an online usertag: `v0idcache`

NOTE: "briefly describe" = 2-3 sentences (and/or include screenshot(s))

Use OSINT techniques to learn as much as you can about `v0idcache` and answer the following questions:

1. What is `v0idcache`'s real name?

v0idcache’s real name is Elizabeth Moffet

2. Where does `v0idcache` work? What is the URL to their website?

v0idcache works at 1337bank, the url to their website is http://1337bank.money/

3. List all personal information (including social media accounts, contacts, etc) you can find about `v0idcache`. For each, briefly detail how you discovered them.

I believe Elizabeth Moffet is from Waterland, Netherlands and I found social media accounts linked to her on
twitter @v0idcache, using usersearch.org with the username “v0idcache”
videobam, using usersearch.org with the username “v0idcache”
flickr, using usersearch.org with the email “v0idcache@protonmail.com”
reddit, using checkusernames.com with the username “v0idcache”


4. List any ( >= 1 ) IP addresses associated with the website. For each, detail the location of the server, any history in DNS, and how you discovered this information.

Using the command nslookup with the bank url at my terminal command line I was able to find the ip address of the website 1337.bank.money, and using yougetsignal.com i found out that port 80 was open
142.93.136.81


5. List any hidden files or directories you found on this website. For full credit, list *two* distinct flags.

http://1337bank.money/secret_directory
CMSC389R-{0M3G4LUL_G3T_pWN3d_N00b}
CMSC389R-{h1ding_fil3s_in_r0bots_L0L}


6. What ports are open on the website? What services are running behind these ports? How did you discover this?

port 80
port 22, ssh something im not too sure

7. Which operating system is running on the server that is hosting the website? How did you discover this?

i think it may be ubuntu, when i tried ncing into the ip with port 22 it said something about ubuntu lol

8. **BONUS:** Did you find any other flags on your OSINT mission? (Up to 9 pts!)

### Part 2

Use the provided python stub code [('stub.py')](stub.py) or write your own program in another language to gain access to `v0idcache`'s server via an open port that you should have found in Part 1.

Once you have gained access to `v0idcache`'s account with the correct login credentials, you will have access to a system shell.

Use your knowledge of Linux and OSINT techniques to locate the flag file and submit its contents for points.

Your response here should briefly document how you approached and solved this part of the assignment. You should also push your bruteforce program to the "week/2/writeup" folder of your GitHub repository.

Note: If you choose to write your own program in another language, please include instructions on how to execute your program, including what version of the language you are using. You will **NOT** receive credit if the TAs cannot run your program.

If you are stuck on this part of the assignment, let us know! The facilitator staff is here to help and teach, and we are open to releasing hints as time goes on!
