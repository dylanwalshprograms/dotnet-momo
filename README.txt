This solution is meant to be a bare bones template for demonstrating how to build and deploy multiple services
from the same .NET solution. I have the solution separated into two files. One for all of your development and one 
for the execution, Inspired by the ideas in "Towards Modern Development of Cloud Applications". 
[link](https://dl.acm.org/doi/pdf/10.1145/3593856.3595909)

Ideal for smaller teams and start ups, this architecture gives the benefits of a distributed
system while maintaining the simplicity and streamlined developer experience of a monolith. The specifics of
the architecture in your solution can be easily swapped out for N-Layer, Clean/Onion, etc and organized however
your teams sees fit. I left this completely empty simply to demonstrate the idea of hosting multiple services from
a single repo. 

I used docker for this template, but this can easily be swapped out for the tool of your choosing.