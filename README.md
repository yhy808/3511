This model code will generate trajectories similar to Figure 1C.
For faster simulation (50 seconds on a 450MHz sparc ultra 10) the
"Quiet" checkbox is on and the trajectories will be displayed at the
end of the run. The checkbox can be turned off during the simulation
to see the them develop but the simulation will run at about 2/3 the
speed.

Nadim F, Manor Y, Nusbaum MP, Marder E.

Frequency regulation of a slow rhythm by a fast periodic input.
J Neurosci 1998 Jul 1;18(13):5053-67

   Many nervous systems contain rhythmically active subnetworks that
interact despite oscillating at widely different frequencies.  The
stomatogastric nervous system of the crab Cancer borealis produces a
rapid pyloric rhythm and a considerably slower gastric mill rhythm.  We
construct and analyze a conductance-based compartmental model to explore
the activation of the gastric mill rhythm by the modulatory commissural
neuron 1 (MCN1)
   This model demonstrates that the period of the MCN1-activated gastric
mill rhythm, which was thought to be determined entirely by the
interaction of neurons in the gastric mill network, can be strongly
influenced by inhibitory synaptic input from the pacemaker neuron of the
fast pyloric rhythm, the anterior burster (AB) neuron.  Surprisingly,
the change of the gastric mill period produced by the pyloric input to
the gastric mill system can be many times larger than the period of the
pyloric rhythm itself.  This model illustrates several mechanisms by
which a fast oscillatory neuron may control the frequency of a much
slower oscillatory network.  These findings suggest that it is possible
to modify the slow rhythm either by direct modulation or indirectly by
modulating the faster rhythm. 

PMID: 9634571 [PubMed - indexed for MEDLINE] 

The full text of this article can be seen at www.jneurosci.org.

Note: The NEURON version 5.1 variable step absolute tolerance has been set 
produce a simulation similar to that of the fixed step crank-nicholson
method with dt=.05(ms). For NEURON version 4.3.1, the tolerance can
be set to 0.01 .
