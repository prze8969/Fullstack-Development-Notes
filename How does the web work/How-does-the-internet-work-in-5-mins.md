There is a video provided for it; 

It basically explains some details about how the internet functions

The video is : https://www.youtube.com/watch?v=7_LPdttKXPc&t=46s

It basically explains your computer is connected to the ISP and then to a flow and then to your domain and other stuff

But at every junction there is a router

This router wraps your data

lets say you are sending some data to xyz.com domain

Your data first goes to your home router and then it wrapw the data into a 
packet, then it goes to ISP then the ISP wraps the data into another packet 
before sending it to the main route of the internet and then it gets wrapped 
again before entering the domain, Now this domain unpacks this data, gets your 
response ready, wraps that response in the same way as your data , and this 
reponse keeps on removing the packet from everytime it see the router



The flow is like:

your_comp -> r1 -> isp -> r2 -> main internet road -> r3 -> isp of domain -> r4 -> domain 

now the data travels like

d -> w1d -> w1d -> w2w1d -> w2w1d -> w3w2w1d -> w3w2w1d -> w4w3w2w1d

and the reponse travels as (From the domain to your comp)

w4w3w2w1r  -> w3w2w1r ->  w3w2w1r -> w2w1r -> w2w1r -> w1r -> w1r -> r


Here w1w2w3w4 -> are just wrappers slided upon each other

----x----x----x----x----x----x----x----x----x----x----x----x----x----x---