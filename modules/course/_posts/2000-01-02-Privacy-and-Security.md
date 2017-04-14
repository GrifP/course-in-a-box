II. Privacy and Security
1. Introduction
In recent years, a lot of news have come out about the efforts of government agencies to collect information about people’s telephone conversations, e-mails and other online information. While governments claim that it is a way of keeping their citizens safe, many users are worried about being spied upon.

Internet has many good things, but it also facilitates some crimes. The communication opportunities make it easier to get some dangerous objects, like weapons, and it makes it easier for criminals to gather and stay connected. These are some of the reasons that government agencies use when surveillance programs are uncovered.

On the other hand, this control over the internet, intended to find criminals, usually entails a large amount of data being collected from people who have done nothing wrong and would like to have an anonymous connection.

Along this course, we seek to explain some concepts that have led to traffic surveillance like the deep web, we will take a look at the current state of affairs explaining concepts like backdoors, and we will ponder some questions about the future.

We will also go over some advice in order to protect our privacy (from anyone, including malicious spies) and some concepts like encryption and Wi-Fi sniffers.

We also suggest some group activities in order to assimilate these concepts better, and we end we a brief conclusion on the topic.

To begin, let us ask ourselves, how much of our personal information are we willing to give up in order to be safer? We will come back to this during the activities.

2. About privacy
A. Deep web
After some of events of the last few years, especially those involving terrorist attacks, many governments have expressed their wish to increase the amount of information they have on internet users in order to better prevent this kind of attacks from happening again.

Although the scandals involving governments which have triggered the privacy and security debate come from monitoring “usual” internet activity, other kinds of connections are also monitored. We are talking about the deep web or invisible web.

The deep web are the contents of the internet which are not indexed by usual search engines, that is, they will not be linked from the search results of a standard search engine. This can happen for a variety of reasons, like if the paged is not linked to from any other page, in which case the search engine will not be able to find it or if it can only be accessed with certain credentials (like a password) or software (like Tor). Although it is hard to determine for certain, it is estimated that the deep web is several hundred times larger than the surface web (the parts that are indexed).

The deep web has a lot of useful content, like private pages of banks and things like that, but some parts of the deep web are intentionally hidden from normal connections and can only be accessed using special networks like Tor or I2P. Here, a lot of illegal activities go on, being drug markets one of the most common, but also others like gun markets, illegal pornography or trade of stolen items. It is also used by some (like Wikileaks) for anonymous whistleblowing.

Surfing the dark web is not impossible, and there are multiple pages that show us how, but it can be dangerous, since we can be exposed to many illegal activities, and many of the contents we can find are fake and designed to lure us in in order to scam us. If you wish to explore this world we recommend that you first inform yourself thoroughly on how to completely protect yourself through anonymization and other tools like virtual machines (programs that simulate a whole operating system inside yours, which can be kept isolated).

B. Tor
Tor is a project that strives to give internet users the possibility of an anonymous connection, that is, that a user’s activity cannot be traced back to them. It received the Award for Projects of Social Benefit in 2010, given by the Free Software Foundation for “[enabling] roughly 36 million people around the world to experience freedom of access and expression on the Internet while keeping them in control of their privacy and anonymity”

Using Tor makes it more difficult to censor or monitor access to certain kinds of content, so it is used when the identity of the user wants to be kept hidden, like when exchanging confidential information.

Tor uses a complex system of encryptions and decryptions in several stages that prevents even the destinataries, who see the decrypted information, from knowing its origin. However, the decrypted information can still be intercepted at the exit nodes, so, while the source will not be detectable, the information might be compromised. To avoid this, other security measures can be taken, like using HTTPS instead of HTTP.

To get an approximate idea of how Tor works, let us imagine the following scenario: You and your friends decided to hold a Secret Santa. The problem is you don’t know how to get your presents to their destinataries without them knowing where they came from, so you decide to do the following. Everyone wraps their present with several layers of wrapping paper, each with a nametag on it, the innermost one containing the name of the intended final recipient. Then, each person gives their gift to the person indicated by the outermost tag. Once you receive a gift, you remove one layer of wrapping paper and then give it to the person whose name you found underneath. Follow this rule until everyone gets a present with a single layer of wrapping paper, which they remove to find their corresponding gift.

This is basically how Tor works: the information is wrapped in several layers of encryption and are then sent through a series of routers that unwrap the encryption layers as they pass it on. When it reaches its final destination, it is impossible to know exactly from which routers it came. Of course, there are more complex mechanisms in place to ensure that the packages really follow the intended course and that it is not possible to trace them back.

C. Backdoors
As new measures have been put into place, it is claimed that we should not worry, since it is necessary to sacrifice a small amount of freedom or privacy in order to greatly increase our security, and that if we are not engaging in any criminal activity this should not affect us at all. However, others claim that this surveillance will affect us negatively if we are anything but harmless, uninteresting and conformist members of society. This vision is expressed in the following video:

https://www.youtube.com/watch?v=pcSlowAhvUk

One of the methods used to access our private information is through backdoors. A backdoor is a method of bypassing authentication mechanisms in an application. They can be used to access contents relevant to security issues, but it also opens up the possibility of accessing private data of a personal nature belonging to innocent citizens.

Often, backdoors are implemented as part of the program itself, which a priori only enables the programmers themselves to use it. This decreases the amount of people who can access our data, but the possibility is still there. In this case, the existence of the backdoor is often kept secret by the developers.

D. The Future
There are multiple opinions on how this debate between security, and privacy and freedom, will end. Maybe these positions aren’t really incompatible and we can find a way to increase security without sacrificing our rights to privacy and freedom. 

Increasingly, laws are being made to ensure the privacy of internet users, but it is also important to guarantee the safety of people from attacks. 

Here is a video of how someone pictures internet privacy in the future: 

https://www.youtube.com/watch?v=uZ8d2P53N1w

It is interesting to consider the point of view of the speaker: the situation towards which we seem to be heading resembles in some way that of a small town, in which everyone knows what everyone else is doing without a lot of fuss about it. Maybe we should ask ourselves whether, since our “small town” has evolved so much, we should also evolve in our privacy policy.

3. Tips
A. Data Encryption
Data encryption is the process of encoding information, thus preventing others from accessing it without the proper key.

Doing this, we can communicate with someone else without having third parties reading the messages we exchange (or at least not directly), and to protect stored information. There is a whole scientific branch studying the systems that make this kind of communication possible: cryptography.

As we said, cryptography is used to establish secure communications, and store and transmit sensitive data, like passwords, authentication information, credit card numbers… and it is very extensively used in many applications, like those involving bank payments, to protect the user's’ information.

However, while here we will talk about its applications to internet communication, cryptography exists since before the internet. One of the best known examples is the Enigma code used by the German military during World War II, which was broken by the codebreakers at Bletchley Park, with the notable contribution of Alan Turing. If we go further back we can find evidence of cryptography since several millennia ago.

Encryption is one of the methods we can use to protect our privacy. These are some of the possibilities:

Encryption of stored data:
Storage devices (hard disks, flash drives, etc): we can encrypt whole storage units, not allowing access to them from a different computer or without a password. We can also encrypt specific partitions of the unit. It is also possible to encrypt certain files or directories so you don’t need to desencrypt everything every time. We can find programs that can encrypt our data, and some operating systems also offer this possibility, but be sure to remember how to desencrypt it afterwards!
Password protection: We can protect some of our files with a password. Some programs, like LibreOffice or Acrobat allow you to directly save your files with password protection. There are also some programs like 7-Zip that compress and encrypt any of your files. This kind of encryption is not the most secure, but it can suffice for many uses.
Encrypted emails: our emails are easy to intercept, so if we want to keep these messages private we have several options. To start with, we can encrypt any attached documents to the email, allowing only the intended recipient access to it. There are also several services which offer encryption of the messages themselves.

B. Wifi Sniffers
A packet analyzer or sniffer is a program that intercepts and analyzes packets that travel through a given network.

There is a lot of traffic that carries confidential information, and, in many cases, it is not encrypted. In this case, a sniffer might intercept it and steal the information for someone else.

There are many kinds of sniffers used for a variety of things, but here we will focus on Wi-Fi sniffers. These sniffers can be introduced, for example, in open Wi-Fi networks in order to monitor unencrypted traffic generated by any user who connects to it.

The following advice should be taken into account when connecting to a Wi-Fi network, especially an open one, since most do not encrypt the communications.

Don’t connect automatically to public Wi-Fi networks and avoid them in general.
When using a public Wi-Fi network, access only secure services (like websites that use HTTPS).
When using a public Wi-Fi network, try to exchange the least amount of personal data possible and avoid connecting to personal accounts.

4. Group activities
A. Internet vs. real world
This activity revolves around our perception of internet and real world surveillance. In all cases, our privacy is diminished, but we might be more willing to accept some of them in order to increase our security.

Each member of the group should take some time to answer whether or not they would allow the following actions:

Being recorded in a supermarket.
Storing your browsing and shopping information in an online store.
Being recorded as you drive through the streets of your city.
Having your navigation history systematically stored.
Having your cash machine activity recorded.
Storing all your online bank activity.

In the odd-numbered questions, real-life situations are presented, whereas in the even-numbered questions, the situations take place on the internet. It is possible that many have been more reluctant to the internet surveillance scenarios.

With the answers previously given, the participants are invited to consider and debate the differences between real-world situations and their internet counterparts. For example, what are your shopping data stored for? Can storing the navigation history of everyone help prevent certain “undesirable” uses of internet, the same way traffic cameras detect infractions? Who is going to know your bank activity and when are they going to use it?

B. The defendant is found…
For this activity we need the participants to take on the following roles:

The judge. Ideally, the person who is teaching the course. You will be the one assumed to be most imparcial.
The robber. You have been arrested robbing a store. You were the only one inside the store, but it was all orchestrated by your colleague, who is now claiming that they were only waiting in the car because they thought that you were only going to buy something. They made you delete the messages in which you talked about it, but you used a sniffer to steal his authentication credentials in order to recover those messages.
The driver. You drove and organized  the robbery, the easy part. Now your colleague has been caught, but you plan on blaming it all on them. The only proof of your implication is a bunch of message which you made them delete, so you think you’ve got a good chance.
The jury. The evidence presented by the robber was not obtained legitimately, but it is the only way of implicating the second culprit. Half the jury must support that the judge use this evidence to make the decision and the other half that using it would set a precedent over allowing violations of privacy. The judge must give out a ruling when they are fully convinced, so it is time to decide, justice or protection?


C. True love
This activity is somewhat long, so you might want to consider that before deciding to do it.

Before starting, every participant must  write down three “secret facts” about themselves. They should be things like “my first tooth fell when I was 5” or “I slept with a stuffed animal until I was 20”, but nothing too obvious. These facts must be kept hidden from everyone else for now. All the participants must make pairs (if there is an odd number of people, the organizer must also participate), and we can start the game.

Valentine’s day is here! You don’t have a partner, so you go to a television program where they pair you up with someone and, if you manage to find out more facts about each other than the other pairs, without them finding out yours, you win a romantic trip to the Caribbean!

The rules are simple: you must convene a code with your partner, but you cannot talk about the facts themselves. After that, you will be separated. Each person will then communicate their facts to their partner publicly, for example, writing them using the convened code on a blackboard (if there is any) that anyone can see. If anyone but the partner finds the fact out, it will not count, so be sure to “encrypt” it well! At the end, the pair which has secretly “decrypted” more facts about each other will win!

Here, you are pretending to play for a trip, but in real life your are playing not to publicly expose your private life.

5. Summary
During this course we have tried to link the concepts of security and privacy, and to show that, while sometimes privacy means security for your personal data, other times security can try to be enforced through a decrease of personal privacy for all.

Privacy is desired by every internet user, but sometimes we have to decide whether we are willing to give it up for our security or the other way around.

We have seen concepts like the deep and the dark web, very little known concepts, Tor, which provides a way of anonymously connecting to the internet, and backdoors, a potential privacy threat. We have also tried to imagine what will happen to privacy in the future.

These concepts lead us to talk about encryption and about the security of our data, which we can summarize in two key pieces of advice:

Don’t send any personal information unless you know from, to and through where you are sending it.
If you want to send anything intended for a single recipient, you should consider whether you want to encrypt it so that it can only be accessed with a certain key.

We hope that the group activities have helped to make the concepts more clear and to make you think about them.

Finally, we repeat the question we posed at the beginning, now with more information to handle it: how much of our personal information are we willing to give up in order to be safer?
