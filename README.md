# Monolith-Tuning-Guide
Tuning Guide for Monolith Gantry Eco Systems

Rules are simple....

**DO NOT SKIP ANY STEPS**

Using Orca Slicer

1. Temp Tower
2. Flow Pass 1 & 2
3. PA Tower(3a.) Flow Pass 2
4. 3x cubes to confirm PA by changing values in live time (cubes at 3 different speeds, 200mm/s, 300mm/s, and 400mm/s)
5. Rerun cube test and change smooth time in live time to see results (roughly every 10-15 layers) start at .004 and work your way DOWN,     lower the better, until quality starts to suffer.
6. Then VFA tower in Orca starting at 150mm/s through 600mm/s
7. Then Accleration testing, 12k-21k, then 22k-31k, 32k-41k, etc... to like 70k.
8. Then IS value testing, run same tests and test X and Y. Go 5hz below and 5hz above the recommended values, 0.5hz steps.
9. Rerun PA
10. Flow Pass 2

11. happy printing
