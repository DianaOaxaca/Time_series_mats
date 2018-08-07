## Supplementary Information

Repository that contain the main data and scripts to recompute the figures from: 

**De Anda V**, Zapata Peñasco I, Blaz J, Poot-Hernandez AC, Contreras Moreira B, Gonzales Laffite Marcos, Hernandez Rosales M, Gamez Tamariz N, Eguiarte Fruns E, Souza V. **Understanding the mechanisms behind the response of environmental perturbations in microbial mats: a metagenomic-network based approach.** Submitted in Frontiers in Microbiology.Research Topic [Characterizing Modern Microbialites and The Geobiological Processes Underlying Their Formation](https://www.frontiersin.org/research-topics/5694/characterizing-modern-microbialites-and-the-geobiological-processes-underlying-their-formation)




To reproduce the figures first install [jupyter notebook](http://jupyter.org/install.html) and then clone the repository.  

```bash
git clone https://github.com/valdeanda/Time_series_mats.git
cd scripts 
ipython3 notebook 
```

### `Requirements`

---

In order to reproduce all the figures the following libraries and packages must be installed first 

`Python`
+ Pandas >= 0.20.3 
+ Numpy >= 1.13.3
+ Seaborn >= 0.8.0
+ Matplotlib >= 2.02

`R packages`
+ Phyloseq
+ ggplot2
+ vegan 
+ pvclust
+ devtools 
+ fpc


###  Figures

---

### `Taxonomic composition, microbial mat core and rare biosphere`

<img src="https://valdeanda.github.io/Time_series_mats/figures/Figure2.png" width="200" height="150" align="right">

Script available in [notebook](https://github.com/valdeanda/Time_series_mats/blob/master/scripts/Diversity.ipynb) format


```bash
jupyter notebook  Diversity.ipynb
```

+ To compute the ecological indexes plase open the following [script](https://valdeanda.github.io/Time_series_mats/scripts/AlfaDiversity.html)  directly in your browser. 

<img src="https://valdeanda.github.io/Time_series_mats/figures/Figure1.png" width="180" height="150" align="righ">

+ To compute the microbial mat core, we used [get_homologues](https://github.com/eead-csic-compbio/get_homologues). The script is available in [notebook](https://github.com/valdeanda/Time_series_mats/blob/master/scripts/Core_bacteria.ipynb) format. 
To repeat the analysis please type in your terminal: 

```bash
jupyter notebook  Core_bacteria.ipynb
```


### `Capturing the dynamics of biogeochemical cycles with MEBS`


<img src="https://valdeanda.github.io/Time_series_mats/figures/Figure6.png" width="200" height="150" align="right">

Script available in  [notebook](https://github.com/valdeanda/Time_series_mats/blob/master/scripts/MebsInTime.ipynb) format. 


```bash
jupyer notebook MebsInTime.ipynb
```

---

+ To compute the metbolic  completeness


Script available in  [notebook](https://github.com/valdeanda/Time_series_mats/blob/master/scripts/completeness.ipynb) format.
Run the notebook

```bash


jupyter notebook completeness.ipynb
```


---

### `Networks`

<img src="https://valdeanda.github.io/Time_series_mats/figures/networkA.png" width="180" height="150" align="right">

The script  is available in [R](https://github.com/valdeanda/Time_series_mats/blob/master/scripts/finalToPlot.R)

---


### `Network motifs`

<img src="https://valdeanda.github.io/Time_series_mats/figures/motifs.png" width="200" height="150" align="right">

Script available in [notebook](https://github.com/valdeanda/Time_series_mats/blob/master/scripts/Motifs.ipynb) format.
Run the notebook

```bash
ipython3 notebook Motifs.ipynb
```
---





### `MORE`

For more information about Cuatro Cienegas please [visit the documentary film](http://documentalcuatrocienegas.com/)

---
