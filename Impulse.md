## Time Course RNA-Seq Analysis and the Impulse Model
<br>
<p align="center">
  <img src="images/Impulse.png" width="460" height="345">
</p>

Beginning in the summer of 2019 at the Harvey Mudd Data Science REU, under the mentorship of Professors Johanna Hardin, Daniel Stoebel, and Danae Schulz, I explored the Impulse models (<a href="https://pubmed.ncbi.nlm.nih.gov/19193146/">Chechik & Koller, Comput. Biol. 16:279–290, 2009</a>), a scaled product of two sigmoidal functions, and its utility in modeling time course RNA-seq data. Time course RNA-seq data violates theoretical assumptions (like independence of samples, since expression values are correlated between time points) that underpin many differential expression algorithms used for analyzing these data. What's more, categorical treatments of time lead to power loss in the ability to detect differentially expressed genes in these experiments.

The model presents a number of advantages to other differential expression methods.

1. The impulse model is a biologically plausible model. The Impulse model can accurately capture transcriptional responses to acute environmental stimuli, while its nested sigmoidal model can capture state-transition/developmental transcriptomic responses.
2. The impulse model treats time as continous, improving power in differential expression analysis as compared to other tools. In fact, the package through which impulse models are fit for differential expression, <a href="https://academic.oup.com/nar/article/46/20/e119/5068248">ImpulseDE2</a>, was determined to be the best performing algorithm in a benchmarking study of time course DE tools (<a href="https://academic.oup.com/bib/article/20/1/288/4364840">Spies, D., et al Brief. Bioinform. 20, 1–11 (2019)</a>).
3. The model is parametrized by biologically meaningful parameters. Particularly the onset time (t1) parameter, which can be used as a proxy for when genes "turn on" during a transcriptional response.

Over the past year, I've conducted methodological inquiry into the model's properties and improving the model fitting procedure. I improved on ImpulseDE2's model fitting procedure by generating many models using random parameter initializations, to avoid local minima fits that weren't descriptive of true expression trends. You can check out a technical report I wrote on this [here](/ImpulseDE2_modeling_writeup.pdf)

I'm continuing methodology-based work on this project by doing a simulation study to understand how to better allocate technical replicates and time points in time course RNA-seq experiments. The goal of this work is to inform the design of time course RNA-seq experiments to obtain better estimation of the onset time parameter.

## Application to time course RNA-seq data for *E. coli* under cell starvation

## Application to time course RNA-seq data for *T. brucei* under bromodomain protein knockout
