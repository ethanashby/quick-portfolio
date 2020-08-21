## About me

My name is Ethan Ashby, and I am a senior mathematics major concentrating in statistics at Pomona College. I’m interested in the application of statistical methods to problems in biology, particularly in the fields of statistical genomics, machine learning, and oncology research.
When I'm not doing stats, I enjoy running, bicycling, & hiking!

---

### Research Projects

[Somatic variant richness for primary site classification in human cancer](/sample_page)
<br>
<img src="images/Word Cloud.jpeg" width="400" height="400">

During the summer of 2020, I worked in the Department of Epidemiology and Biostatistics at Memorial Sloan Kettering Cancer Center under the mentorship of Dr. Ronglai Shen and Dr. Saptarshi Chakraborty to extract clinically-relevant signals from rare mutations in the cancer genome. In previous research, my mentors used nonparametric, Bayesian methods develop in the fields of computational linguistics and ecology to mine tissue-specific signals from rare mutations (in the word cloud above, analogous to the diverse collection of green words) in major cancer genes (Chakraborty et al., Nature Communications 10:1-9, 2019). However, the majority of genes were omitted from analysis due to sparse mutation data.  <br>
We developed a framework to resolvve mutation data sparseness and extend this analysis to all genes in the human genome, by using unsupervised clustering to build gene groups defined by biological variables known to correlate with somatic mutation rate. This project was a step towards harnessing the preponderance of previously neglected mutation data for important clinical purposes. <br>
I am continuing to work on this project for my senior thesis. I intend to assess the performance of different statistical divergence metrics in grouping rare variant probabilities. This will rovide the basis for an information-theoretic clustering approach, where genes are grouped in a manner that increases the tissue specificity of rare variant probabilities. This will help generate clinically-relevant gene groups, which can be useful in diagnosing certain varieties of cancer.

---
[Analysis of Time Course RNA-Seq Data in E. coli and T. brucei](/pdf/sample_presentation.pdf)
<br>
<img src="images/Impulse.png" width="460" height="345">

Beginning in the summer of 2019 at the Harvey Mudd Data Science REU, I began to explore the Impulse models (Chechik & Koller, Comput. Biol. 16:279–290, 2009), a scaled product of two sigmoidal functions, and its utility in modeling time course RNA-seq data. The model is parametrized by biologically-meaningful parameters, including an onset time parameter, which permits researchers to approximate when genes 'turn on' in response to an environmental stimulus. <br>
On the methodological side, I've shown that the impulse and sigmoid models are descriptive of certain expression profiles, but break down when data is sparse. I updated the model fitting procedure of ImpulseDE2 (Fischer, Theis, & Yosef, Nucleic Acids Res. 46, 1–10, 2018), a well-regarded differential expression algorithm for time course RNA-Seq data that relies on these models, to include random parameter initializations. <br>
On the biological side, I've applied this method to time course datasets in E. coli and T. brucei (a human parasite that causes sleeping sickness). In the E. coli experiment, we showed that sensitivity to a stress-responsive transcription factor may act as a mechanism to control gene expression timing in response to cell starvation. In the T. brucei experiment, we used clustering and gene set enrichment to decode whether a knockout of an class of chromatin readers influences life cycle progression in this parasite.

---
[Analysis Antarctic Petrel Foraging Trips](http://example.com/)
<br>
<img src="images/Petrel.png" width="600" height="500">

In the spring of 2020, I visualized and analyzed GPS data for 150 Antarctic Petrel forage trips over the austral summers between 2012-2014. I identified that petrel foraging trip length was highly variable from year to year and used PAM clustering to identify prototype petrel foraging paths. When I integrated the GPS data with remote sensing data for several climatic variables, I identified a phenomenon where petrels tended to forage in regions of low to moderate sea ice cover, corresponding to the sea ice edge. This finding was supported by the scientific literature (Delord, K. et al., R. Soc. Open Sci. 7, 2020). However, there was no correlation between petrel forage location and large icebergs. This project represented a data-driven approach to understand the ecology of an important Antarctic sentinel species. 

---

### Links

- [Project 1 Title](http://example.com/)
- [Project 2 Title](http://example.com/)
- [Project 3 Title](http://example.com/)
- [Project 4 Title](http://example.com/)
- [Project 5 Title](http://example.com/)

---




---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
