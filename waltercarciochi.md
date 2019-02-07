# Soil moisture conditions

**Background:**

A first step in the water balance calculation is to know different moisture conditions of the soil where the crop is growing. Thus, soil water content at drained upper limit (DUP; -0.33 bar) and low limit (LL; -15 bar) are necessary to calculate the plant available water capacity (PAWC) and the water capacity at the critical threshold (CT), value below which crop growth is assumed to be restricted by water availability. The DUP and LL could be measured by the retention curve method but usually, this information is not available, thus an estimation of these soil characteristics could be necessary. 

**Objective:**

Estimate some soil moisture conditions and variables (DUP, LL, PAWC, and CT) from texture and organic matter content. 

**Outcomes:**

Create a model to calculate different soil moisture conditions and variables from some soil characteristics. 

**Diagram:**

![alt_text](https://github.com/waltercarciochi/project/blob/master/Diagram.png)

1. Water capacity at DUP (θ33) and LL (θ1500) will be calculated as suggested by Saxton and Rawls (2006): 

θ<sub>33</sub>=θ<sub>33t</sub>+[1.283(θ<sub>33t</sub>)<sup>2</sup>-0.374(θ<sub>33t</sub>)-0.0015] 

θ<sub>33t</sub>=-0.251S+0.195C+0.011OM+0.006(S*OM)-0.027(C*OM)+.452(S*C)+0.229 

θ<sub>1500</sub>= θ<sub>1500t</sub>+(0.15* θ<sub>1500t</sub>-0.02) 

θ<sub>1500t</sub>=-0.024S+0.487C+0.006OM+0.005(S*OM)-0.013(C*OM)+0.068(S*C)+0.031 

where S is sand content (%w), C clay content (%w), and OM organic matter content (%w)

2. Plant available water capacity (PAWC) will be calculated at the difference between DUP and LL (%v) multiplied by the soil depth (data required). 

3. Soil water capacity at the critical threshold (CT) will be calculated from the PAWC and the critical threshold (%) (data required). 

**References:** 

Saxton, K.E.; Rawls, W.J. 2006. Soil water characteristic estimates by texture and organic matter for hydrologic solutions. Soil Sci SoC Am J. 70:1569–1578.
