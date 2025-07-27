This NEURON model reproduces simmulations shown in the manuscript "Layer 5 myelination gates corticothalamic coincidence detection" by Jamann et al.

Install the latest version of NEURON from https://www.neuron.yale.edu/neuron/
Compile the "L5_long-range model" file using the mknrndll script. 

Two example simulations can be started with the hoc files "Fig. 6d_Suppl_Fig. 8e" or "_Fig. 6e"

In the RunControl window hit "init & run". 

_Fig. 6d_Suppl_Fig. 8e runs a deterministic model evoking a burst of 4 action potentials.  

Using the "Myelin properties" window cortical, white matter or POm demyelination can be selected, and myelin can be reinstalled via the "remyelination" button. This replicates data shown in Supplementary Figure 8e

_Fig. 6e runs the stochastic model with fluctuating voltages mimicking synaptic inputs combined with a 20 ms current injection to evoke a burst with variable action potentials.  

Using the "Myelin properties" window cortical demyelination can be simulated and myelin can be reinstalled via the "remyelination" button. This replicates data shown in Supplementary Figure 8e

For further information; m.kole_at_nin.knaw.nl 

