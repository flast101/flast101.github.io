# Home
* * *

![home.jpg](home.jpg "home.jpg")


**[/usr/bin/whoami](https://flast101.github.io/whoami)**: Me, Myself and I.

**[Hack The Box writeups](https://flast101.github.io/HTB-writeups/)**: here are walkthroughs to root machines on the [HackTheBox](https://www.hackthebox.eu) website, an online platform for learning and teaching cyber security.

Writeups list:   

- _18 July 2020_: [Sauna](https://flast101.github.io/HTB-writeups/sauna) 
- _11 July 2020_: [Book](https://flast101.github.io/HTB-writeups/book) 
- _20 June 2020_: [ServMon](https://flast101.github.io/HTB-writeups/servmon)  
- _13 June 2020_: [Monteverde](https://flast101.github.io/HTB-writeups/monteverde)   
- _31 May 2020_: [Resolute](https://flast101.github.io/HTB-writeups/resolute)   


# Blog   

* * *
_07 August 2020_
## Reverse Shell Cheat Sheet
You can find them in a lot of places. Here are the one I could find here and there.    
_[Read more ...](https://flast101.github.io/reverse-shell-cheatsheet)_   

* * * 
_04 July 2020_     
## Padding Oracle Attack
**Padding Oracle attack fully explained and coded from scratch in Python3.**

The padding oracle attack is a spectacular attack because it allows to decrypt a message that has been intercepted if the message was encrypted using CBC mode. POODLE (Padding Oracle On Downgraded Legacy Encryption) is a man-in-the-middle exploit which takes advantage of Internet and security software clients' fallback to SSL 3.0. If attackers successfully exploit this vulnerability, on average, they only need to make 256 SSL 3.0 requests to reveal one byte of encrypted messages.   
It will only require ensuring that we are able to obtain a response from the server that will serve as an Oracle (we'll come back to these in more detail later in this report). We will then be able to decrypt the entire message except the first block, unless we know the initialization vector.   

In this article, we will focus on how to use this vulnerability and propose a python script that exploits CBC mode to decrypt a message encrypted in AES-CBC.    
_[Read more ...](https://flast101.github.io/padding-oracle-attack-explained)_   


<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-173692234-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-173692234-1');
</script>

