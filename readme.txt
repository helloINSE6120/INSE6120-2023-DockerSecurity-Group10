Capability


When it comes to the Linux operating system, root users are treated like royalty and granted privileged access. If I can divide these extraordinary talents into smaller parts, I will have capabilities.

By default, Docker drops all capabilities except those needed it uses a whitelist approach to do that. I can use Docker commands to add on remove it is to or from the bonding set.>>>>Script1&Script2: 



 
Now what I can do is I can spin up another container using Docker run.>>>> Script3

What I am essentially doing is dropping the capability from this container.  

This means I have successfully drop this CHWON capability from this container.

 

 

Assume that I want to drop all the capabilities from the container and add only one specific capability of our choice. >>>Script4


 
Only one capability which is “capsh” this time even though all the capabilities are dropped we will still be able to perform this CH on operation in this container.
This is how we can make use of capabilities to have granular control on what privileges the root accounts.
