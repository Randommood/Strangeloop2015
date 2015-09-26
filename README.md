# Architectural patterns of resilient distributed systems

Accompanying repository for the "Architectural patterns of resilient distributed systems" talk given at [Strangeloop 2015](http://www.thestrangeloop.com/2015/sessions.html). Feel free to open any issues for questions and/or to say hi :)

## Talk Outline
See the [image credits](credits.md), link to [slides](https://speakerdeck.com/randommood/architectural-patterns-of-resilient-distributed-systems), and [video-soon](#).

* Why Resilience
 * Motivation & Definitions
* Resilience Literature
 * Harvest/Yield thinking
 * Cook's Model
 * Borrill's Model
* Resilience in industry
 * Netflix
 * Google
 * Fastly
* Conclusions
 * Back to the start
 * Parting thoughts and rantifestos

## References

### Resilience literature
* [Baller checklist on things to remember](http://monkey.org/~marius/checklist.pdf)
* [Harvest, Yield, and Scalable Tolerant Systems](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.24.3690&rep=rep1&type=pdf)
* [Computer Immunology - Burgess](http://people.scs.carleton.ca/~soma/biosec/readings/burgess-immunology.pdf)
* [Building Robust Systems an essay - Sussman](http://groups.csail.mit.edu/mac/users/gjs/6.945/readings/robust-systems.pdf)
* [How Complex Systems Fail - Cook](http://web.mit.edu/2.75/resources/random/How%20Complex%20Systems%20Fail.pdf)
* [Optimal Design, Robustness, and Risk Aversion](http://tuvalu.santafe.edu/~jdf/papers/optimal.pdf)
* [Part Count and Design of Robust Systems](http://meche.mit.edu/documents/danfrey/danfrey_partcount.pdf)
* [Highly Optimized Tolerance: A Mechanism for Power Laws in Designed Systems](http://snap.stanford.edu/class/cs224w-readings/carlson99tolerance.pdf)
* [Fault Tolerance and the Five-Second Rule](https://www.usenix.org/system/files/conference/hotos15/hotos15-paper-chen_ang.pdf)
* [Scale free Networks - computerworld](http://www.computerworld.com/article/2579374/networking/scale-free-networks.html)
* [The Scale-free property - Barabási](http://barabasilab.neu.edu/networksciencebook/download/network_science_december_ch4_2013.pdf)
* [Scale-free network](https://en.wikipedia.org/wiki/Scale-free_network)
* [Resilient Distributed Datasets: A Fault-Tolerant Abstraction for In-Memory Cluster Computing](https://www.cs.berkeley.edu/~matei/papers/2012/nsdi_spark.pdf)
* [Failure Sketches: A Better Way to Debug](https://www.usenix.org/conference/hotos15/workshop-program/presentation/kasikci)
* [Virtual Network Diagnosis as a Service](https://research.facebook.com/publications/616093585136896/virtual-network-diagnosis-as-a-service/)
* [‘Going solid’: a model of system dynamics and consequences for patient safety](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC1743994/pdf/v014p00130.pdf)
* [Building on Quicksand](http://db.cs.berkeley.edu/cs286/papers/quicksand-cidr2009.pdf)
* [Immutability Changes Everything](http://www.cidrdb.org/cidr2015/Papers/CIDR15_Paper16.pdf)
* [You can't sacrifice partition tolerance](http://codahale.com/you-cant-sacrifice-partition-tolerance/)
* [Complex adaptive system](https://en.wikipedia.org/wiki/Complex_adaptive_system)
* [Robustness principle](https://en.wikipedia.org/wiki/Robustness_principle)
* [Small-world experiment](https://en.wikipedia.org/wiki/Small-world_experiment)

### Resilience in industry
* [Fault tolerance in a high-volume distributed system](http://techblog.netflix.com/2012/02/fault-tolerance-in-high-volume.html)
* [From Chaos to Control - Testing the resiliency of Netflix’s Content Discovery Platform](http://techblog.netflix.com/2015/08/from-chaos-to-control-testing.html)
* [Making the Netflix API More Resilient](http://techblog.netflix.com/2011/12/making-netflix-api-more-resilient.html)
* [Google Finds: Centralized Control, Distributed Data Architectures Work Better Than Fully Decentralized Architectures](http://highscalability.com/blog/2014/4/7/google-finds-centralized-control-distributed-data-architectu.html)
* [Clients are Jerks: aka How Halo 4 DoSed the Services at Launch & How We Survived](http://caitiem.com/2015/06/23/clients-are-jerks-aka-how-halo-4-dosed-the-services-at-launch-how-we-survived/)
* [Game Day Exercises at Stripe: Learning from kill -9](https://stripe.com/blog/game-day-exercises-at-stripe)
* [How we ended up with microservices](http://philcalcado.com/2015/09/08/how_we_ended_up_with_microservices.html)
* [Postmortem for July 27 outage of the Manta service](https://www.joyent.com/blog/manta-postmortem-7-27-2015)
* [Hashicorp Yamux](https://github.com/hashicorp/yamux)
* [The Chubby lock service for loosely-coupled distributed systems](http://static.googleusercontent.com/media/research.google.com/en//archive/chubby-osdi06.pdf)
* [Summary of the Amazon DynamoDB Service Disruption and Related Impacts in the US-East Region](https://aws.amazon.com/message/5467D2/)

### Media
* [Velocity NY 2013:   Richard Cook, "Resilience In Complex Adaptive Systems"](https://www.youtube.com/watch?v=PGLYEDpNu60&feature=youtu.be)
* [Developing a Globally Distributed Purging System](https://www.youtube.com/watch?v=HfO_6bKsy_g) and [slides](https://speakerdeck.com/brucespang/papers-prototypes-and-production-developing-a-globally-distributed-purging-system)
* [Complex Adaptive Systems: 13 Robustness & Resilience](https://www.youtube.com/watch?v=HOTWIPmkdzo)
* [Network Theory: 16 Robustness & Resilience](https://www.youtube.com/watch?v=_ztNkmDg0mw)
* [Design of Resilient Systems - Innovations in Thinking Differently](https://www.youtube.com/watch?v=nV52yh6GDMg)
* [Camille Fournier's Papers We Love Talk on The Chubby lock service for loosely-coupled distributed systems](https://www.youtube.com/watch?v=PqItueBaiRg) and [slides](https://speakerdeck.com/hakka_labs/the-chubby-lock-service-for-loosely-coupled-distributed-systems)
* [Scaling Networks through Software](https://www.usenix.org/conference/srecon15/program/presentation/taveira)

# Thank you!
Thank you to everyone who helped with feedback/resources and advice for this talk. Special thanks to: Paul Borrill, Jordan West, Caitie McCaffrey, Camille Fournier, Mike O'Neill, Neha Narula, Matt Whiteley, Joao Taveira, Tyler McMullen, Zac Duncan, Nathan Taylor, Ian Fung, Armon Dadgard, Peter Alvaro, Peter Bailis, Alex Rasmussen, Bruce Spang, Aysulu Greenberg, and Greg Bako.
