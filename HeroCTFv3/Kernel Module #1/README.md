# Kernel Module #1

##### Situation :
Hey sweetheart !
I left a little something for you in the safe.
It's unlocked, so you just have to retrieve it.
Love you ! xoxo
##### PS : Happax, the cat, has been behaving oddly lately..
1. We connect on the channel via SSH
2. When connected we see a file called run. We execute it to start the challenge.
3. When we execute run we can see :
* ![chall](https://github.com/C0R4Y4/image/blob/main/unknown2.png)
4. So we first think of the most common commands to read a file : cat /dev/safe
Which gives us a really funny thing:
* ![result](https://github.com/C0R4Y4/image/blob/main/cat.png) 
5. So it looks like the flag is sont in /dev/safe but when we do cat we have :
* ![result](https://github.com/C0R4Y4/image/blob/main/cat.png)
6. I understood that the command cat wasn't the one we all knew.
7. So I use a different command to read a file
8. tail /dev/safe which show us the flag.
