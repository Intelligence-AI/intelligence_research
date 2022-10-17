# Research on Generalizable and Universal Principles of Intelligence For Application & Systems Design In Business, Code, and Data


## [Universal Intelligence: A Definition of Machine Intelligence](https://arxiv.org/pdf/0712.3329.pdf)
*Shane Legg, Marcus Hutter*

A fundamental problem in artificial intelligence is that nobody really knows what intelligence is. The problem is especially acute when we need to consider artificial systems which are significantly different to humans. In this paper we approach this problem in the following way: We take a number of well known informal definitions of human intelligence that have been given by experts, and extract their essential features. These are then mathematically formalised to produce a general measure of intelligence for arbitrary machines. We believe that this equation formally captures the concept of machine intelligence in the broadest reasonable sense. We then show how this formal definition is related to the theory of universal optimal learning agents. Finally, we survey the many other tests and definitions of intelligence that have been proposed for machines.





## [On the Measure of Intelligence](https://arxiv.org/pdf/1911.01547.pdf)
*François Chollet*

To make deliberate progress towards more intelligent and more human-like artificial systems, we need to be following an appropriate feedback signal: we need to be able to define and evaluate intelligence in a way that enables comparisons between two systems, as well as comparisons with humans. Over the past hundred years, there has been an abundance of attempts to define and measure intelligence, across both the fields of psychology and AI. We summarize and critically assess these definitions and evaluation approaches, while making apparent the two historical conceptions of intelligence that have implicitly guided them. We note that in practice, the contemporary AI community still gravitates towards benchmarking intelligence by comparing the skill exhibited by AIs and humans at specific tasks such as board games and video games. We argue that solely measuring skill at any given task falls short of measuring intelligence, because skill is heavily modulated by prior knowledge and experience: unlimited priors or unlimited training data allow experimenters to "buy" arbitrary levels of skills for a system, in a way that masks the system's own generalization power. We then articulate a new formal definition of intelligence based on Algorithmic Information Theory, describing intelligence as skill-acquisition efficiency and highlighting the concepts of scope, generalization difficulty, priors, and experience. Using this definition, we propose a set of guidelines for what a general AI benchmark should look like. Finally, we present a benchmark closely following these guidelines, the Abstraction and Reasoning Corpus (ARC), built upon an explicit set of priors designed to be as close as possible to innate human priors. We argue that ARC can be used to measure a human-like form of general fluid intelligence and that it enables fair general intelligence comparisons between AI systems and humans.



## [On the Principles of Parsimony and Self-Consistency for the Emergence of Intelligence](https://arxiv.org/abs/2207.04630)
*Yi Ma, Doris Tsao, Heung-Yeung Shum*

Ten years into the revival of deep networks and artificial intelligence, we propose a theoretical framework that sheds light on understanding deep networks within a bigger picture of Intelligence in general. We introduce two fundamental principles, Parsimony and Self-consistency, that address two fundamental questions regarding Intelligence: what to learn and how to learn, respectively. We believe the two principles are the cornerstones for the emergence of Intelligence, artificial or natural. While these two principles have rich classical roots, we argue that they can be stated anew in entirely measurable and computable ways. More specifically, the two principles lead to an effective and efficient computational framework, compressive closed-loop transcription, that unifies and explains the evolution of modern deep networks and many artificial intelligence practices. While we mainly use modeling of visual data as an example, we believe the two principles will unify understanding of broad families of autonomous intelligent systems and provide a framework for understanding the brain.


## [A free energy principle for the brain](https://www.fil.ion.ucl.ac.uk/~karl/A%20free%20energy%20principle%20for%20the%20brain.pdf)
*Karl Friston, James Kilner, Lee Harrison*

By formulating Helmholtz’s ideas about perception, in terms of modern-day theories, one arrives at a model of perceptual inference
and learning that can explain a remarkable range of neurobiological facts: using constructs from statistical physics, the problems of inferring the causes of sensory input and learning the causal structure of their generation can be resolved using exactly the same principles.
Furthermore, inference and learning can proceed in a biologically plausible fashion. The ensuing scheme rests on Empirical Bayes and
hierarchical models of how sensory input is caused. The use of hierarchical models enables the brain to construct prior expectations in a
dynamic and context-sensitive fashion. This scheme provides a principled way to understand many aspects of cortical organisation and
responses.
In this paper, we show these perceptual processes are just one aspect of emergent behaviours of systems that conform to a free energy
principle. The free energy considered here measures the difference between the probability distribution of environmental quantities that
act on the system and an arbitrary distribution encoded by its configuration. The system can minimise free energy by changing its configuration to affect the way it samples the environment or change the distribution it encodes. These changes correspond to action and
perception respectively and lead to an adaptive exchange with the environment that is characteristic of biological systems. This treatment
assumes that the system’s state and structure encode an implicit and probabilistic model of the environment. We will look at the models
entailed by the brain and how minimisation of its free energy can explain its dynamics and structure.

## [Collective dynamics of ‘small-world’ networks](https://static.squarespace.com/static/5436e695e4b07f1e91b30155/t/54452561e4b08d9eb2170909/1413817697054/collective-dynamics-of-small-world-networks.pdf)
*Duncan J. Watts & Steven H. Strogatz*

Networks of coupled dynamical systems have been used to model biological oscillators1–4, Josephson junction arrays5,6, excitable media, neural networks, spatial games, genetic control networks and many other self-organizing systems. Ordinarily, the connection topology is assumed to be either completely
regular or completely random. But many biological, technological and social networks lie somewhere between these two extremes. Here we explore simple models of networks that can be tuned through this middle ground: regular networks ‘rewired’ to introduce increasing amounts of disorder. We find that these systems can be highly clustered, like regular lattices, yet have small characteristic path lengths, like random graphs. We call them
‘small-world’ networks, by analogy with the small-world phenomenon (popularly known as six degrees of separation). The neural network of the worm Caenorhabditis elegans, the power grid of the western United States, and the collaboration graph of film actors are shown to be small-world networks.
Models of dynamical systems with small-world coupling display enhanced signal-propagation speed, computational power, and synchronizability. In particular, infectious diseases spread more easily in small-world networks than in regular lattices.

## [Grandmaster level in StarCraft II using multi-agent reinforcement learning](https://www.nature.com/articles/s41586-019-1724-z)
*Oriol Vinyals, Igor Babuschkin, Wojciech M. Czarnecki, Michaël Mathieu, Andrew Dudzik, Junyoung Chung, David H. Choi, Richard Powell, Timo Ewalds, Petko Georgiev, Junhyuk Oh, Dan Horgan, Manuel Kroiss, Ivo Danihelka, Aja Huang, Laurent Sifre, Trevor Cai, John P. Agapiou, Max Jaderberg, Alexander S. Vezhnevets, Rémi Leblond, Tobias Pohlen, Valentin Dalibard, David Budden, David Silver*

Many real-world applications require artificial agents to compete and coordinate with other agents in complex environments. As a stepping stone to this goal, the domain of StarCraft has emerged as an important challenge for artificial intelligence research, owing to its iconic and enduring status among the most difficult professional esports and its relevance to the real world in terms of its raw complexity and multi-agent challenges. Over the course of a decade and numerous competitions1,2,3, the strongest agents have simplified important aspects of the game, utilized superhuman capabilities, or employed hand-crafted sub-systems4. Despite these advantages, no previous agent has come close to matching the overall skill of top StarCraft players. We chose to address the challenge of StarCraft using general-purpose learning methods that are in principle applicable to other complex domains: a multi-agent reinforcement learning algorithm that uses data from both human and agent games within a diverse league of continually adapting strategies and counter-strategies, each represented by deep neural networks5,6. We evaluated our agent, AlphaStar, in the full game of StarCraft II, through a series of online games against human players. AlphaStar was rated at Grandmaster level for all three StarCraft races and above 99.8% of officially ranked human players.
