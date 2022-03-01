# Cookies - picoCTF 2021
Who doesn't love cookies? Try to figure out the best one. http://mercury.picoctf.net:6418/    
## Web Exploitation - 40 Points - Hints: (none)

Going into this challenge I have a clue from the title "cookies" that this has something to do with the web cookies so I had my cookie editor open. 

So the first thing I did was check the cookies, I saw it was set to -1 by default, so I tried setting it to 1 and I got a red herring saying "I love chocolate chip cookies!".

After not finding anything in the HTML, I proceeded to manually brute force the cookie value. Once I reached 18 it displayed the flag: "picoCTF{3v3ry1_l0v3s_c00k135_88acab36}"
