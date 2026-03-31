# PreACT

We conducted a stress test in Cooperative Navigation where three identical agents are initialized at the exact same coordinates in every episode. PreACT robustly achieves a reward of -0.36 ± 0.02, significantly outperforming the MAPPO baseline (-0.48 ± 0.15). The two gifs show that MAPPO frequently falls into a local optimum where agents conflict over the same landmark. Conversely, PreACT successfully negotiates and accurately disperses the agents to distinct targets without entering deadlocks or experiencing symmetry-induced oscillations.
