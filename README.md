# Phase coherence Kmeans
## Credits
### Pablo CASTRO main contributor to the code
### Supervised by Rodrigo COFRE and Alain DESTEXHE
### Rodrigo COFRE main contributor to the article
#### Authors and co-authors: Pablo Castro, Andrea Luppi, Enzo Tagliazucchi, Yonatan S-Perl, Lorina Naci, Adrian M. Owen, Jacobo D. Sitt, Alain Destexhe, Rodrigo Cofré
## Github repository for [this](https://doi.org/10.1101/2023.12.19.572402) publication
#### (In case the link doesn't work: P.CASTRO et al, 2023, Biorxiv, https://doi.org/10.1101/2023.12.19.572402)


## Overview
To analyze brain dynamics from functional magnetic resonance imagery, we computed, for each brain region (Region Of Interest, ROI) and each repetition time (TR), the instantaneous phase of the analytical continuation of the BOLD signal. 
We then extracted how the phases from different ROIs synchronize (or anti-synchronize) to obtain coherence patterns. 
After that, we clustered those patterns using an unsupervised machine-learning algorithm. 
Next, we analyzed how the frequencies of occurrences of the obtained stereotypical brain patterns change depending on the condition (in our case general anesthesia versus wakefulness and recovery, as well as awake versus N3 deep sleep). We focused our analysis on the relationship between structure and function to show that, under states of low/loss of consciousness, the brain patterns were much more similar to the anatomical backbone than under wakeful states, where no/little tendency is noticeable, and that during unwakefulness, the entropy (Shannon) was significantly lower than when conscious, demonstrating that loss of consciousness is associated/due to perturbation in the brain dynamics that make them more predictable, less surprising, less random. 
We finally extended our analysis by considering the Markov assumption (memoryless stochastic process) to construct a Markov chain linking together the obtained 'cliché' brain states. This allowed us to show preferential state transitions depending on the condition, as well as a reduction of the entropy under unconscious states when compared to wakeful ones.

### Loading data
We prepared a dummy timeserie to illustrate the functionalities of our study, we invite fellow researchers to try using their data with multiple conditions to perform comparisons.



