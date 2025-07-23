# GMI
## Generative Mechanism Index v0.1

The Generate Mechanism Index is a benchmark for generative design applications to score how well they are doing. It serves to quantify the dificulty of the problem (how non-obvious the solution is) and the applications ability to solve that problem. Thus it is a function of the following:

### Problem Dificulty Criteria:
-Spatial Resolution (G): # of volumetric elements (e.g. 50³ vs. 100³)

-Degrees of Freedom (D): required output motions or force paths

-Load Complexity (L): # of distinct load cases

-Boundary Regions (B): # of fixed/support areas

-Morphological Complexity (M): feature-count or surface-area-to-volume ratio


### Solution Performance Criteria:
-Convergence Time (T): wall-clock to reach performance threshold

-Iteration Count (I): solver or optimizer steps to converge

-Optimality Gap (ΔO): (achieved objective – theoretical best)/theoretical best

-Constraint Violation (CV): % of constraints unmet

-Material Efficiency (VE): volume used vs. minimum required




### Basic Mechanisms (PCI 1-3):
-Force inverters  
-Displacement amplifiers  
-Simple grippers

### Intermediate Mechanisms (PCI 4-6):
-Multi-stable switches
-Coupled motion generators
-Precision positioning stages

### Advanced Mechanisms (PCI 7-9):
-Multi-input/multi-output systems
-Mechanisms with embedded sensing regions
-Frequency-selective structures

### Expert Level (PCI 10+):
-Full assemblies (micro-engines, pumps)
-Mechanisms with thermal/electrical coupling
-Self-assembling or morphing structures
