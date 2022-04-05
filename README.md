# OrcaFlex-Snapback
OrcaFlex simulation of a rope snapback test: OrcaFlex installation required. 

This simulation is a proof-of-concept, based on some rough assumptions about the test setup based on the previous well-documented Zarga rope failure incident. 
The rope was modelled as a Nylon construction of 100 Tonnes MBL, breaking at 50 Tonnes. The simulation requires an extremely small time step of 5 micro-seconds, which is 10000 times smaller than normal marine simulations. Other tweaks are needed to get the simulation to solve.
The simulation is sensitive to the modelling variables, so there is no replacement for testing at this stage; more data points are needed. 

See ORE Catapult blog post for reference: 
https://ore.catapult.org.uk/blog/mooring-rope-snapback-simulation/?utm_content=203319068&utm_medium=social&utm_source=linkedin&hss_channel=lcp-3318975

Based on the test performed by Holmes for BHP: 
https://www.holmessolutions.com/bhp-understanding-marine-snapbacks-case-study-video-release/  
