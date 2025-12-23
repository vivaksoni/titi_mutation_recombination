# titi_mutation_recombination
<h2><b>Repository for Soni et al. 2026: Inferring fine-scale rates of mutation and recombination in the coppery titi monkey (<i>Plecturocebus cupreus</i>) </h2></b> 
<b>Vivak Soni1, Cyril J. Versoza, Jeffrey D. Jensen, and Susanne P. Pfeifer.</b>

<br></br>
Divergence: fine_scale_divergence folder contains divergence maps for different window sizes: {window_size}_divergence.SNPable.bed.xz files contain divergence values across different window sizes. Files contain the following columns: chromosome name, window start coordinates, window end coordinates, number of accessible sites, number of point mutations between P. cupreus and humans, divergence. For code to plot divergence and mutation rate maps, see jupyter notebook file, titi_plot_divergenceMaps.ipynb.

<br></br>
Recombination: LDhelmet_empirical_inference contains inferred recombination rates using LDhelmet, with rates averaged over 1mb windows. Results are for block penalties of 5, 10, 20, and 50. benchmarking_vcf folder contains vcf files for simulations performed in msprime for the purposes of benchmarking recombination methods under the titi demographic model. LDhelmet_benchmarking folder contains LDhelmet results files for benchmarking.
