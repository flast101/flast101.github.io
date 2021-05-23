# Home
_My Infosec Blog - Be Curious, Learning Is Life !_
* * *

_$ ls -la .contact: [flast101.sec@gmail.com](mailto:flast101.sec@gmail.com)_   

![home.jpg](home.jpg "home.jpg")


**[$(whoami)](https://flast101.github.io/whoami)**: Me, Myself and I.

**[Hack The Box writeups](https://flast101.github.io/HTB-writeups/)**: here are walkthroughs to root machines on the [HackTheBox](https://www.hackthebox.eu) website, an online platform for learning and teaching cyber security.

Writeups list:   

- _10 october 2020_: [Cache](https://flast101.github.io/HTB-writeups/cache)   
- _22 August 2020_: [Magic](https://flast101.github.io/HTB-writeups/magic)   
- _15 August 2020_: [Traceback](https://flast101.github.io/HTB-writeups/traceback)   
- _18 July 2020_: [Sauna](https://flast101.github.io/HTB-writeups/sauna)   
- _11 July 2020_: [Book](https://flast101.github.io/HTB-writeups/book)   
- _20 June 2020_: [ServMon](https://flast101.github.io/HTB-writeups/servmon)   
- _13 June 2020_: [Monteverde](https://flast101.github.io/HTB-writeups/monteverde)    
- _31 May 2020_: [Resolute](https://flast101.github.io/HTB-writeups/resolute)    


# Blog   

* * *
_23 may 2021_    
## PHP 8.1.0-dev Backdoor Remote Command Execution    
**PHP 8.1.0-dev Backdoor System Shell Script**   

An early release of PHP, the PHP 8.1.0-dev version was released with a backdoor on March 28th 2021, but the backdoor was quickly discovered and removed. If this version of PHP runs on a server, an attacker can execute arbitrary code by sending the User-Agentt header.   
The following exploit uses the backdoor to provide a pseudo system shell on the host.     
_[Read more ...](https://flast101.github.io/php-8.1.0-dev-backdoor-rce/)_   

* * *
_9 August 2020_    
## Abusing Docker Configuration    
**Privilege escalation in Docker**   

In this article, I talk about a classic privilege escalation through Docker containers. This is a very well known trick used when the configuration let too many accounts run docker, and you will have to do it in some CTF boxes at least. Unfortunately, it is not always correcly understood.        
I had a lot of fun the first time I encountered it in PWK lab as wells as the second time on a HTB machine.         
Let's see what it is about.     
_[Read more ...](https://flast101.github.io/docker-privesc/)_   

* * *
_7 August 2020_
## Reverse Shell Cheat Sheet    
**My Reverse Shell Cheat Sheet**   

You can find them all around the internet. I couldn't find them all in one place, so I write them down here. Don't hesitate to tell me if you find some more and I will add them to this list.    
_[Read more ...](https://flast101.github.io/reverse-shell-cheatsheet)_   

* * * 
_4 July 2020_     
## Padding Oracle Attack   
**Padding Oracle attack fully explained and coded from scratch in Python3**

The padding oracle attack is a spectacular attack because it allows to decrypt a message that has been intercepted if the message was encrypted using CBC mode. POODLE (Padding Oracle On Downgraded Legacy Encryption) is a man-in-the-middle exploit which takes advantage of Internet and security software clients' fallback to SSL 3.0. If attackers successfully exploit this vulnerability, on average, they only need to make 256 SSL 3.0 requests to reveal one byte of encrypted messages.   
It will only require ensuring that we are able to obtain a response from the server that will serve as an Oracle (we'll come back to these in more detail later in this report). We will then be able to decrypt the entire message except the first block, unless we know the initialization vector.   

In this article, we will focus on how to use this vulnerability and propose a python script that exploits CBC mode to decrypt a message encrypted in AES-CBC.    
_[Read more ...](https://flast101.github.io/padding-oracle-attack-explained)_   

* * *
_Be Curious, Learning is Life !_

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-173692234-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-173692234-1');
</script>

