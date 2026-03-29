Lets cconsider two computers
How can they be connected to each other??

Ethernet, or a data cable.

But its only limited to those two computers

What if we want to connect three??

Its simple we would actually connect all the three computers with three different ethernet cables

But what about 4?
computer1 (c1) -(connects to)-> c2,c3,c4
c2 -> c3,c4
c3 -> c4

But what if we want to send a packet directly from c1 to c4 without having transvered the other computers?

so we need an architecture like 
c1->c2,c3,c4
c2 -> c1,c3,c4
c3->c1,c2,c4
c4->c1,c2,c3

Now we can see it requires a LOT of wires

Is there a better way to do it>??
Yes there is
A switch

A switch is a device that links n diffirent computers with n different wires not (nP2)

It connects according to our need

Its basic connections are

c1,c2,c3,c4 -> switch(s)

If we want to connect c1 to c2,
its happens like
c1 -> s -> c2
 
Similarly if we want c2 to c4
c2 -> s -> c4


This is great and all for a small team/group working on same project and want to share smt in between the locaal computers

But if we want to share it globally, the wries wont be long enough so we have to come up with alternatives


The alternative we have is a router(r),
A router uses the old telephone lines to carry a single from a switch to other swtiches

Switches can be grouped as trees too, but it becomes more and more task heavy for switches to do that, hence router is a key thing to do

Now there are companies that provide ISP (Internet service provider)

This ISP has a speacial kind of routers which connects other special routers of other ISP, connecting the whole world

In short :

c1,c2,c3,c4 -> s1 -> r1
c5,c6,c7,c8 -> s2 -> r1

c9,c10,c11,c12 -> s3 -> r2
c13,c14,c15,c16 -> s4 -> r2

r1,r2 -> ISP1



c1,c2,c3,c4 -> s1 -> r3
c5,c6,c7,c8 -> s2 -> r3

c9,c10,c11,c12 -> s3 -> r4
c13,c14,c15,c16 -> s4 -> r4

r3,r4 -> ISP2

and then 
ISP1 <-> ISP2



Now lets talk about what is an IP

An IP is Internet protocol, or a address to a computer
It is unique to each computer

If we want to send a message to a computer we have to know their IP

But its too tedious to byhard the ip of each computer, if we are on intenet

Hence people have made "Domain" , which is like the human readable form of ip

so the stuff like google.com is tied to the IP like 142.--.--.-.0



Lets now talk about the internet,Intranet and Extranet


The Bubble is like first comes in intranet, the smallest then the extranet which includes the intranet but excludes the internet and then comes the internet

Now, what is intranet?
Intranet is the network of computers joint together locally
like in a single company 

What is extranet?
Extranet is the network of computers not only joint locally but also joint by some outside collaborators and some customers

Intenet?
It literally connects every single person with a device and connection



Thats it for this chapter.
        

----x----x----x----x----x----x----x----x----x----x----x----x----x----x---