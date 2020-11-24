# RE-STORM: **Re**quirement**s** Trade-offs for self adaptation using Partially **O**bse**r**vable **M**arkov Decision Processes (POMDPs)

**RE-STORM** is a technique to support reasoning and decision making based on the trade-offs of NFRs by Self Adaptive Systems (SASs), and underpinned by POMDPs.

Paper submitted to http://www.sosym.org/ 

[1] Luis Garcia-Paucar, Nelly Bencomo. Requirements Trade-offs for Self-adaptation using Requirements-aware Runtime Models based on Partially Observable Markov Decision Processes.

## Acknowledgements 

This work has been partially funded by the Leverhulme Trust Research Fellowship (Grant No. RF-2019-548/9) and the EPSRC
Research Project Twenty20Insight (Grant No. EP/T017627/1).


## Abstract  

Self-adaptive  and  autonomous  system  (SAS)  is  a  system  that adapts its behaviour accordingly to environmental fluctuations. The decision-making process of a SAS is challenged by the underlying uncertainty, which brings up possible unforeseen situations. In this paper, we focus on the uncertainty associated with the satisficement levels of the quality properties, i.e. the non-functional requirements (NFRs) of a SAS, due to adaptation actions under unpredictable environments. The levels of satisficement of the NFRs are seen as variables that are partially observable by a set of monitorable variables. The trade-offs among NFRs (i.e. the qualities of a system) are embodied as a Partially Observable Markov Decision Processes (POMDP). Uncertainty is represented as “beliefs” (i.e. as probability distributions over the satisficement levels of NFRs given a system configuration and a set of observations), while the trade-offs of the NFRs guide the decision making of the self-adaptation. The experiments show that for newly found unforeseen situations during the execution, initial design parameters, such as preferences over NFRs and adaptation  actions,  can  be  reassessed  by  the  SAS  to  maintain  the  Service  Level Agreements (SLAs). It was demonstrated that these reassessments of preferences under the current environment allowed for improved decision-making.

 ## Log files
The log files used to generate the results depicted in [1] have been organized in three categories:

* System under Dynamic Context (folders DynamicContext_DC1 to DynamicContext_DC2)
* Other Service Level Agreements (SLAs) (folder Other SLAs)
* System Under stable conditions (folder _StableConditions)

Each folder contains the .json files utilized to generate the plots presented in [1]. Specifically:


* Figure 7 and Figure 8, correspond to the log files:

/DynamicContext_DC1/_logi_c1_s10_YesDNoJ.json and

/DynamicContext_DC1/_logi_c1_s10_YesDYesJ.json


* Figure 9 and Figure 10, correspond to the log files:

/DynamicContext_DC3/_logi_c3_s10_YesDNoJ.json and

/DynamicContext_DC3/_logi_c3_s10_YesDYesJ.json


* Figure 11 and Figure 13, correspond to the log files:

/DynamicContext_DC2/_logi_c3_s10_YesDNoJ.json and

/DynamicContext_DC2/_logi_c3_s10_YesDYesJ.json


* Figure 12 and Figure 14, correspond to the log files:

/DynamicContext_DC3/_logi_c4_s10_YesDNoJ.json and

/DynamicContext_DC3/_logi_c4_s10_YesDYesJ.json




