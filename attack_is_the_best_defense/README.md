# Attack is the best defense

<img src="https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/01c5a1e3f29d290b188d34be5cf534d3255058a7.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240320%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240320T082118Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=8c5ede777757264f2e2eb66c7108fade653a7267e44e6dbcd7bc854441d18832">

<p>Security is a vast topic, and network security is an important part of it. A lot of very sensitive information goes over networks that are used by many people, and some people might have bad intentions. Traffic going through a network can be intercepted by a malicious machine pretending to be another network device. Once the traffic is redirected to the malicious machine, the hacker can keep a copy of it and analyze it for potential interesting information. It is important to note that the traffic must then be forwarded to the actual device it was supposed to go (so that users and the system keep going as if nothing happened).</p>

<p>Any information that is not encrypted and sniffed by an attacker can be seen by the attacker - that could be your email password or credit card information. While today’s network security is much stronger than it used to be, there are still some legacy systems that are using unencrypted communication means. A popular one is telnet.In this project, we will not go over ARP spoofing, but we’ll start by sniffing unencrypted traffic and getting information out of it.</p>

Sendgrid offers is an emailing service that provides state of the art secure system to send emails, but also supports a legacy unsecured way: telnet. You can create an account for free, which is what I did, and send an email using telnet</p>
