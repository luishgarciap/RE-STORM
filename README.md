# RE-STORM: **Re**quirement**s** Trade-offs for self adaptation using Partially **O**bse**r**vable **M**arkov Decision Processes (POMDPs)

**RE-STORM** is a technique to support reasoning and decision making based on the trade-offs of NFRs by Self Adaptive Systems (SASs), and underpinned by POMDPs.

Paper submitted to http://www.sosym.org/ 
[1] Luis Garcia-Paucar, Nelly Bencomo. Requirements Trade-offs for Self-adaptation using Requirements-aware Runtime Models based on Partially Observable Markov Decision Processes.

## Acknowledgements 

This work has been partially funded by the Leverhulme Trust Research Fellowship (Grant No. RF-2019-548/9) and the EPSRC
Research Project Twenty20Insight (Grant No. EP/T017627/1).


## Abstract  

self-adaptive  and  autonomous  system  (SAS)  is  a  system  thatadapts its behaviour accordingly to environmental fluctuations. The decision-making process of a SAS is challenged by the underlying uncertainty, whichbrings up possible unforeseen situations. In this paper, we focus on the un-certainty associated with the satisficement levels of the quality properties, i.e.the non-functional requirements (NFRs) of a SAS, due to adaptation actionsunder unpredictable environments. The levels of satisficement of the NFRs areseen as variables that are partially observable by a set of monitorable variables.The trade-offs among NFRs (i.e. the qualities of a system) are embodied asa Partially Observable Markov Decision Processes (POMDP). Uncertainty isrepresented as “beliefs” (i.e. as probability distributions over the satisficementlevels of NFRs given a system configuration and a set of observations), whilethe trade-offs of the NFRs guide the decision making of the self-adaptation.The experiments show that for newly found unforeseen situations during theexecution, initial design parameters, such as preferences over NFRs and adap-tation  actions,  can  be  reassessed  by  the  SAS  to  maintain  the  Service  LevelAgreements (SLAs). It was demonstrated that these reassessments of prefer-ences under the current environment allowed for improved decision-making

 ## Log files
The paper results have been organized in three categories:

* System under Dynamic Context (folders DynamicContext_DC1 to DynamicContext_DC2)
* Other Service Level Agreements (SLAs) (folder Other SLAs)
* System Under stable conditions (folder _StableConditions)

Each folder contains the .json files utilized to generate the plots presented in [1]. 

