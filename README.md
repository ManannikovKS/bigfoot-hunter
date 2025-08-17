# Bigfoot Hunter
This notebook aims to demonstrate my knowledge of stochastic processes and hypothesis testing using a toy problem. This is one of the tasks that I solved during my half-year interaction with Barack Zackay's 'Statistics in Astrophysics' lab in Weizmann.

So the aim of the problem is to track a Bigfoot!:)

Imagine a 2d forest, partitioned into 100x100 squares. If Bigfoot passes through the forest, it does it in the following manner: Starting from the left, in each step, it moves either to one square right, right top, or right bottom. When it passes through a square, it will leave footprints in probability 70%. In squares it did not pass through, there is a 10% probability that footprints will appear randomly (this is also true if Bigfoot did not pass through the forest).

The notebook consists of 2 main parts:
1) Given a map of footprints, write a test that answers the question "Was there a Bigfoot?" (derivations is in test_derivation.pdf)
2) Given a map of footprints, reconstruct Bigfoot's path.
