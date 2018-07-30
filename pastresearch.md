---
layout: page
title: Past Research
permalink: /pastresearch/
---

These are research areas that I have worked on during the past few years.
For my current research work click <a href="/research/">here</a>.

<h1>Intelligent Transportation Systems</h1>
<img class="alignleft" src="/images/traffic.png" style="width: 335px;"/>

<p>Nowadays, the field of Intelligent Transportation Systems has raised increasing interest. Transport optimization, either for individuals or fleets, has significant social, economical and environmental impact. Incorporating the effect of traffic in routing by forecasting travel times is an interesting, yet challenging problem, which could have a positive impact on the effectiveness of urban transportation systems. Research in this area aims to design and develop novel techniques for achieving the best possible accuracy in vehicle traffic prediction, avoiding jams and detecting incidents.</p>

<p>The work in this area was performed while I was working as a research associate in the EU-funded project eCOMPASS (eCO-friendly urban Multi-modal route PlAnning Services for mobile uSers). Upon studying these problems and reviewing different methodologies, my colleagues and I analyzed the effect of correlation and PCA metrics when interpreting traffic data. We designed and implemented <a target="_blank" href="http://ieeexplore.ieee.org/document/6728266/">a new prototype algorithmic variation of STARIMA</a>, based on the use of a global Coefficient of Determination on road speeds. Additionally, we designed <a target="_blank" href="https://trid.trb.org/view.aspx?id=1316918">a novel traffic jam prediction algorithm and a traffic jam visualisation approach</a> based on cluster analysis that effectively identifies dense congestion areas.</p>


<h1>Multi-Agent Systems</h1>
<h2>Ad-hoc Cooperation of Agents</h2>
<img class="alignright" src="/images/adhocagents.png" style="width: 335px;"/>

<p>The problem of autonomous agents cooperating effectively has always been an interesting problem for the area of Multi-Agent Systems. Since agents in cooperative scenatios are usually a priori coordinated towards their common goals, in situations where no prior coordination is possible, current solutions may fall short. Such situations are described as ad hoc team settings and the challenge is to design an autonomous agent that shall construct models of his teammates' strategies, determine which model is followed by each of his teammates, and finally devise an efficient strategy to effectively cooperate with them.</p>

<p>The work performed in this area has been the subject of my <a target="_blank" href="/files/AdhocTeamFormation.pdf">master thesis</a> for the MSc Degree in Computer Science from the University of Edinburgh, supervised by Dr. Michael Rovatsos. As part of this work, we have designed an ad hoc agent that is able to cooperate with his teammates without being a priori aware of their strategies. At first, we constructed a methodology for extracting data instances from observed state-action pairs, and trained a classifier in order to predict the actions of any teammate given the system state. After that, we employed a bayesian model to estimate the probability of a teammate following a specific model given his actions. Then, the strategy of our agent involves using Q-learning policies as answer models to any combination of teammates' models. Finally, our implementation was tested for its effectiveness and efficiency in a search-and-rescue testbed.</p>

<h2>Multi-Agent Systems for the Energy Market</h2>
<img class="alignleft" src="/images/energyagent.png" style="width: 335px;"/>

<p>The area of Double Auctions is one of the most interesting fiels, since research so far has not arisen any optimal solution, therefore it is considered as an open problem for the future. A typical example of a Double Auction market are Energy Markets, which in their modern form are free and decentralized. In these types of markets, energy producers and consumers transact with each other via brokers. Brokers are system agents that ensure the smooth flow of energy among the producers and the consumers with whom they have signed contracts. Designing such an autonomous agent is a challenging task.</p>

<p>The work performed in this area has been the subject of my diploma thesis (available <a target="_blank" href="/files/AuctionEnergyMarket.pdf">here</a> in Greek) for the Diploma Degree in Electrical and Computer Engineering from the Aristotle University of Thessaloniki, supervised by Dr. Andreas Symeonidis and Dr. Anthony Chrysopoulos. As part of this work, we have designed an <a target="_blank" href="http://link.springer.com/chapter/10.1007/978-3-642-40864-9_3">agent-broker</a> for <a target="_blank" href="http://www.powertac.org/">Power TAC</a>, a platform designed to model the modern energy market as well as to encourage the development of new innovative strategies of intelligent agents and decision making. Our agent involves the design of the following strategies: an adaptive and predictive price formation strategy to determine the price of the next ask or bid, a fuzzy shout update strategy to determine whether a new ask or bid should be placed, and an energy prediction strategy that forecasts the energy to be consumed by the consumers of the market using time series analysis.</p>
