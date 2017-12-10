This repo will contain source code and documentation (progress and ideas) for my work on usable privacy and security infrastructure.

# Inspiration
- I loved Jeff Huang's essay [Ph.D. 2.0: Adopting the Startup Culture for Research](http://jeffhuang.com/adopting_the_startup_culture_for_research.html). Take-aways: 
  - "wow" products/demos > papers
  - reliable code and documentation (eg., Colin Raffel's PhD thesis) > flimsy academic code that that is unusable to anyone else
  - risky attempts at creating "magical" results > safe incremental 
  - feedback loops with users (DAWN project)
  - share work with the public ("how will this look in *the* paper") through **expository writing** (Michael Nielsen [essays](https://distill.pub/2017/aia/) or Zachary Lipton's *[The Mythos of Model Interpretability](https://arxiv.org/pdf/1606.03490v2.pdf)*
  - **create compelling demos on the web or in real life** (examples: https://clickclickclick.click,  my style transfer mirror at SNU's Convocation 2017)
- Philip Rogaway's paper *[The Moral Character of Cryptographic Work](http://web.cs.ucdavis.edu/~rogaway/papers/moral-fn.pdf)*.
- **[You and Your Research](https://www.cs.virginia.edu/~robins/YouAndYourResearch.html)** by Richard Hamming.
- **[You can do research too](http://www.bailis.org/blog/you-can-do-research-too/)**. An essay by Peter Bailis.
- [Briar and Bramble: A Vision for Decentralized Infrastructure](https://dymaxion.org/essays/briarvision.html)

# TODO:

- [ ] **Product goal**: Build an email service based on the paper **Deploy-It-Yourself(DIY) Hosting for Online Privacy** - enabled by cheap serverless computing and secured by container isolation and a key manager.

> Web users today rely on centralized services for applications such as email, file transfer and chat. Unfortunately, these services create a significant privacy risk: even with a benevolent provider, a single breach can put millions of users’ data at risk. One alternative would be for users to host their own servers, but this would be highly expensive for most applications: a single VM deployed in a high-availability mode can cost many dollars per month. In this paper, we propose Deploy It Yourself (DIY), a new model for hosting applications based on serverless computing platforms such as Amazon Lambda. DIY allows users to run a highly available service with much stronger privacy guarantees than current centralized providers, and at a dramatically lower cost than traditional server hosting. DIY only relies on the security of container isolation and a key manager as opposed to the large codebase of a high-level application such as Gmail (and all the Google teams using Gmail data). With attestation technology such as SGX, DIY’s execution could also be verified remotely. We show that a DIY email server that sends 500 messages/day costs $0.26/month, which is 50× cheaper than a highly available EC2 server. We also implement a DIY chat service and show that it performs well. Finally, we argue that DIY applications are simple enough to operate that cloud providers could offer a simple “app store” for using them.
> https://cs.stanford.edu/~matei/papers/2017/hotnets_diy.pdf

- [ ] **Differential Privacy tools for achieving Bramble project's vision** - Briar/Bramble folks seemed eager to listen to my ideas. Pitch DP-based solutions for collecting user data (randomized response and RAPPOR), private messaging (Stadium) and private queries (Splinter).
- [ ] **Reaching out to the tech community**: A demo and talk at [ChennaiPy](http://chennaipy.org/),
- [ ] **Reaching out to the general public**: The public **CAN** be made to realize the gravity of cutting-edge research (example: the Computational Social Science guy at Stanford received tonnes of mail from people who were viscerally hurt/shocked when they heard that Facebook manipulated sentiment of their news feed to study its affect of their behaviour)
