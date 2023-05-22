# Python_Climate_Change
**Motivation**

-Game theory offers a lot to whether or not countries decide to engage in 
climate action.

-The “players” end up being the individual countries that try to choose options that would help them secure the best outcomes for themselves.

-They then engage in “games” that embrace the idea of interdependence where the outcomes for the “players” or countries depend on what strategies others act on.

-Climate change can be treated as an iterated game where there is a common-pool resource that is available to everyone. If managed correctly, these resources can sustain and provide value to many parties, but when too much is taken too quickly, the resource can easily be depleted.

-Therefore, the “game” must be set up in a way to reward cooperation and stop individual “players” from free riding from other’s contributions.

-We will try to recreate the results from the paper  "Climate change governance, cooperation and self-organization"


**Context**

The most recent report of the Intergovernmental Panel on Climate Change (IPCC) accumulates evidence that human activity is responsible for most of the Global Warming we have witnessed since the 50s. The recent World summits set up to work out a solution to Global Warming have added up to a (now) long list of unsuccessful attempts to solve the Climate Change problem. Despite  i) the actual risk of collective disaster, ii) the scientific consensus that anthropogenic greenhouse gas (GHG) emissions perturb global climate patterns with negative consequences for many ecosystems and iii) the predictions of early warning signals and severe climate change consequences that are already in place, such as increased occurrence of heat waves and droughts .


**Problem Statement** - *The Game We Cannot Afford to Lose*

We want to use Evolutionary Game Theory to model how a group of N people interact in a Public Goods Game (PGG) where there is an introduced risk factor. We take into account how individual behaviors change over time based on the decisions and achievements of others, which influence one's own decisions. This process is described in the framework of EGT. 
Additionally, we want consider the dynamics of small and finite populations and incorporate spontaneous exploration of possible strategies, which adds to the overall randomness of the process. 


**The Model**

Model describes individuals in a population of size N. Each individual has an initial endowment b and is classified as either a Cooperator (C) or a Defector (D) based on their behavior regarding climate issues. Cooperators contribute a fraction cb of their endowment, while Defectors do not contribute anything. The goal is to reach a certain threshold of contributions to the public good             , and if successful, all participants keep their endowments. If the threshold is not met, with a probability of r (the risk of collective disaster), everyone in the group loses their endowment.

  We adopt a dynamical approach, in which individuals revise their strategies through peer-influence, copying others whenever these appear to be more successful. Such social learning (or evolutionary, in the sense of cultural evolution) approach allows policies to change in time as individuals are influenced by the behavior (and achievements) of others, something one actually witnesses in the context of donations to public goods . This also takes into account the fact that agreements may be vulnerable to renegotiation.

