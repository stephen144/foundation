# {{ page.title }}

## Feature Velocity

This chapter introduces some of the stakeholders in computer
networks—network designers, application developers, end users, and
network operators—to help motivate the technical requirements that
shape how networks are designed and built. This presumes all design
decisions are purely technical, but of course, that’s usually not the
case. Many other factors, from market forces, to government policy,
to ethical considerations, influence how networks are designed and
built.

Of these, the marketplace is highly influential, and corresponds to
the interplay between network operators (e.g., AT&T, Comcast, Verizon,
DT, NTT, China Mobile), network equipment venders (e.g., Cisco,
Juniper, Ericsson, Nokia, Huawei, NEC), application and service
providers (e.g., Facebook, Google, Amazon, Microsoft, Apple, Netflix,
Spotify), and of course, subscribers and customers (i.e., individuals,
but also enterprises and businesses). The lines between these players
are not always crisp, with many companies playing multiple roles. The
most notable example of this are the large cloud providers, who (a)
build their own networking equipment using commodity components, (b)
deploy and operate their own networks, and (c) provide end-user
services and applications on top of their networks.

When you account for these other factors in the technical design
process, you realize there are a couple of implicit assumptions in the
textbook version of the story that need to be reevaluated. One is that
designing a network is a one-time activity. Build it once and use it
forever (modulo hardware upgrades so users can enjoy the benefits of
the latest performance improvements). A second is that the job of
building the network is largely divorced from the job of operating the
network. Neither of these assumptions is quite right.

The network’s design is clearly evolving, and we have documented these
changes with each new edition of the textbook. Doing that on a
timeline measured in years has historically been good enough, but
anyone that has downloaded and used the latest smartphone app knows
how glacially slow anything measured in years is by today’s standards.

On the second point, the companies that build networks are almost
always the same ones that operate them. They are collectively known as
*network operators*, and they include the companies listed above. But
if we once again look to the cloud for inspiration, we see that
develop-and-operate isn’t true just at the company level, but it is
also how the fastest moving cloud companies organize their engineering
teams: around the *DevOps* model. (If you are unfamiliar with DevOps,
we recommend you read *Site Reliability Engineering: How Google Runs
Production Systems* to see how it is practiced.)

What this all means is that computer networks are now in the midst of
a major transformation, with network operators trying to
simultaneously accelerate the pace of innovation (sometimes known as
feature velocity) and yet continue to offer a reliable service
(preserve stability). And they are increasingly doing this by adopting
the best practices of cloud providers, which can be summarized as
having two major themes: (1) take advantage of commodity hardware and
move all intelligence into software, and (2) adopt agile engineering
processes that break down barriers between development and operations.

This transformation is sometimes called the “cloudification” or
“softwarization” of the network, but by another name, it is known as
*Software Defined Networks* (SDN). Whatever you call it, this new
perspective is a game changer, not so much in terms of how we address
the fundamental technical challenges of framing, routing,
fragmentation/reassembly, packet scheduling, congestion control,
security, and so on, but in terms of how rapidly the network evolves
to support new features.

This transformation is so important that we take it up again in the
*Broader Perspective* section at the end of each of chapter. As these
discussions will explore, what happens in the networking industry is
partly about technology, but also partly about many other
non-technical factors, all of which is a testament to how deeply
embedded the Internet is in our lives.

> [!NOTE|label:Broader Perspective]
> To continue learning about the cloudification of the Internet, see
> [Race to the Edge](../direct/trend.md)
