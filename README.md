# Home
* * *

**[About](https://flast101.github.io/about):** Me, Myself and I.

**[Hack The Box writeups](https://flast101.github.io/HTB-writeups/)**: here are walkthroughs to root machines on the [HackTheBox](https://www.hackthebox.eu) website, an online platform for learning and teaching cyber security.

Writeups list:   

- _31 May 2020_: [Resolute](https://flast101.github.io/HTB-writeups/resolute)   
- _13 June 2020_: [Monteverde](https://flast101.github.io/HTB-writeups/monteverde)   
- _20 June 2020_: [ServMon](https://flast101.github.io/HTB-writeups/servmon)  
- _10 July 2020_: [Book](https://flast101.github.io/HTB-writeups/book) 
- _Soon_: [Sauna](https://flast101.github.io/HTB-writeups/sauna) 


# Blog
* * *

_04 July 2020_   
**Padding Oracle Attack**: Padding Oracle attack fully explained and coded from scratch in Python3.

The padding oracle attack is a spectacular attack because it allows to decrypt a message that has been intercepted if the message was encrypted using CBC mode. 
It will only require ensuring that we are able to obtain a response from the server that will serve as an Oracle (we'll come back to these in more detail later in this report). We will then be able to decrypt the entire message except the first block, un less you know the initialization vector.   

In this article, we will focus on how to use this vulnerability and propose a python script that exploits CBC mode to decrypt a message encrypted in AES-CBC.

_[Read more ...](https://flast101.github.io/padding-oracle-attack-explained)_   
