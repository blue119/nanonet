The idea is inspired from mininet. I'd like to build a network lab on one host.
before I hvae to create multiple VM instance and bundle them network together
with bridge interface. This way is heavy on VM instance cost.

As I saw mininet, It can build a SDN lab with Linux namespace. splitting
instance's namespace that make them don't see each other, and them bundle them
with virtual link. With namespace to build a isolating instance is pretty
slightly costing. the cost is almost same as one terminal process's cost.

But the mininet is built for SDN lab. Most time I need a lab to prove my
netowrk topology, routing, L2 forwarding, tc concept, but I don't need te SDN
controller. So I'd like to build a simple script like as mininet to built a
lab w/o SDN controller. I can do whatever networking thing on this lab and
lightly resource cost.

