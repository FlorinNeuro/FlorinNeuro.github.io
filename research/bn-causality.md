---
title: Causal inference
---
# {% include icon.html icon="fa-solid fa-connectdevelop" %}Causal inference

{% include tags.html tags="MEG, LFP" link="research" %}

<!-- Figures -->

Most of the network analyses stick to correlative investigations. However, brain networks often require the identification of causal influences. A common approach is using Granger causality-based methods that rely on the temporal ordering of time series. Despite its common use, a detailed evaluation of the reliability of different competing causality measures was largely missing in the literature. We closed this gap by systematically evaluating their relative performance and sensitivity to preprocessing and laid the groundwork for their proper use in neuroscience. Employing theoretical arguments and simulation results, we showed that pre-processing without a strong prior about the artifact to be removed disturbs the information content and time ordering of the data and leads to spurious and missed causalities (Florin et al., 2010 & 2011 ; Weber et al., 2016).

<!-- Citations -->

E. Florin, J. Gross, J. Pfeifer, G.R. Fink, L. Timmermann (2011): Reliability of multivariate causality measures for neural data. Journal of Neuroscience Methods, 198(2):344-58. 

E. Florin, J. Gross, J. Pfeifer, G.R. Fink, L. Timmermann (2010): The effect of filtering on Granger causality derived multivariate causality measures. NeuroImage, 50(2): 577-588. 

I. Weber, E. Florin, M. von Papen, L. Timmermann (2017): The influence of filtering and downsampling on the estimation of transfer entropy, PLoS One, 12(11): e0188210. 
