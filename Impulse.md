## Time Course RNA-Seq Analysis and the Impulse Model

Beginning in the summer of 2019 at the Harvey Mudd Data Science REU, under the mentorship of Professors Johanna Hardin, Daniel Stoebel, and Danae Schulz, I explored the Impulse models (<a href="https://pubmed.ncbi.nlm.nih.gov/19193146/">Chechik & Koller, Comput. Biol. 16:279–290, 2009</a>), a scaled product of two sigmoidal functions, and its utility in modeling time course RNA-seq data. Time course RNA-seq data violates theoretical assumptions (like independence of samples, since expression values are correlated between time points) that underpin many differential expression algorithms used for analyzing these data. What's more, categorical treatments of time lead to power loss in the ability to detect differentially expressed genes in these experiments.

The model presents a number of advantages to other differential expression methods.

1. The impulse model is a biologically plausible model. The Impulse model can accurately capture transcriptional responses to acute environmental stimuli, while its nested sigmoidal model can capture state-transition/developmental transcriptomic responses.
2. The impulse model treats time as continous, improving power in differential expression analysis as compared to other tools.
3. The model is parametrized by biologically meaningful parameters. Particularly the onset time $t_1$ parameter, can be used as a proxy for when genes "turn on" during a transcriptional response.

Over the past year, I've conducted methodological inquiry into the model's properties and improving the model fitting procedure. 

## Application to time course RNA-seq data for *E. coli* under cell starvation

## Application to time course RNA-seq data for *T. brucei* under bromodomain protein knockout
