---
layout: page
title: Landis Lab @ WUSTL - Research
current: 
class: 'home-template'
navigation: True
---

<br>
# Research

Models of evolutionary processes help us understand how biodiversity is generated, sustained, and lost.
Primary research interests for the Landis Lab include [historical biogeography](#historical-biogeography), the [evolution of ecological interactions](#evolution-of-ecological-interactions), [phenotypic evolution](#phenotypic-evolution), and [statistical phylogenetics](#phylogenetic-inference-with-revbayes).
We study evolution by developing probabilistic models, writing open source and community-minded software, and analysing simulated and empirical data.
These methods are available as open source software (see below).
We maintain a broad and active interest in phylogenetic inference, and develop for [RevBayes](http://revbayes.com), an open-source package for modeling evolutionary processes and estimating trees.

---

### Historical biogeography

Historical biogeography studies the distribution of species in space and time.
Because many species have no known fossil record, biogeographers often rely on reconstructing ancestral species ranges to understand how ranges change over time.
Only recently, statistical event-based models have been used in a phylogenetic context to estimate ancestral species ranges, represented presence-absence states for sets of discrete areas.
Methodologically, we are interested in techniques to allow the models to be applied to high-resolution, global-scale datsets.
For models, we are interested how biogeographic inference may improve phylogenetic estimates.

#### Related work

<table>
    
    <!-- NEW ENTRY -->
    <tr>
        <!-- IMAGE -->
        <td><table table-layout="fixed" style="margin:auto" width="200px">
            <td markdown="span" width="200px">
                <img src="/assets/research/img/Landis_et_al_2022_PNAS_fig_model.png" style="float: left; margin:0px" height="100" width="200" class="img-circle-5">
            </td>
        </table></td>
        <!-- PAPER -->
        <td><table table-layout="fixed" style="margin:auto">
            <td markdown="span">
                **MJ Landis**, I Quintero, MM Muñoz, F Zapata, MJ Donoghue. 2022. Phylogenetic inference of where species spread or split across barriers. Proceedings of the National Academy of Sciences 119: e2116948119.<br>
                [[paper](/assets/research/pdf/Landis_et_al_2022_PNAS_FIG_biogeo_model.pdf)]  [[scripts](http://github.com/mlandis/fig_model)]
            </td>
        </table></td>
    </tr>
    
    <!-- NEW ENTRY -->
    <tr>
        <!-- IMAGE -->
        <td><table table-layout="fixed" style="margin:auto" width="200px">
            <td markdown="span" width="200px">
                <img src="/assets/research/img/Landis_et_al_2021_SystBiol_viburnum_phylo.png" style="float: left; margin:0px" height="100" width="200" class="img-circle-5">
            </td>
        </table></td>
        <!-- PAPER -->
        <td><table table-layout="fixed" style="margin:auto">
            <td markdown="span">
                **MJ Landis**, DAR Eaton, WL Clement, B Park, EL Spriggs, PW Sweeney, EJ Edwards, MJ Donoghue. 2021. Joint phylogenetic estimation of geographic movements and biome shifts during the global diversification of Viburnum. Systematic Biology 70: 67-85.<br>
                [[paper](/assets/research/pdf/Landis_et_al_2021_SystBiol_viburnum_phylo.pdf)]  [[scripts](http://github.com/mlandis/vib_div)]
            </td>
        </table></td>
    </tr>

    <!-- NEW ENTRY -->
    <tr>
        <!-- IMAGE -->
        <td><table table-layout="fixed" style="margin:auto" width="200px">
            <td markdown="span" width="200px">
                <img height="100px" width="200px" src="/assets/research/img/Landis_et_al_2018_Evolution_silversword_radiation.png" style="float: left; margin:0px" class="img-circle-5">
            </td>
        </table></td>
        <!-- PAPER -->
        <td><table table-layout="fixed" style="margin:auto">
            <td markdown="span">
                **MJ Landis**, WA Freyman, BG Baldwin. 2018. Retracing the silversword radiation despite phylogenetic, biogeographic, and paleogeographic uncertainty. Evolution, 72:2343-2359.<br>
                [[paper](/assets/research/pdf/Landis_et_al_2018_Evolution_silversword_radiation.pdf)]  [[scripts](http://github.com/mlandis/biogeo_silversword)]
            </td>
        </table></td>
    </tr>
    
    
    <!-- NEW ENTRY -->
    <tr>
        <!-- IMAGE -->
        <td><table table-layout="fixed" style="margin:auto" width="200px">
            <td markdown="span" width="200px">
                <img src="/assets/research/img/Landis_2016_SystBiol_biogeographic_dating.png" style="float: left; margin:0px" height="100" width="200" class="img-circle-5">
            </td>
        </table></td>
        <!-- PAPER -->
        <td><table table-layout="fixed" style="margin:auto">
            <td markdown="span">
                **MJ Landis**. 2017. Biogeographic dating of speciation times using paleogeographically informed processes. Systematic Biology, 66:128-144.<br>
                [[paper](/assets/research/pdf/Landis_2017_SystBiol_biogeographic_dating.pdf)]  [[scripts](http://github.com/mlandis/biogeographic_dating)]
            </td>
        </table></td>
    </tr>
    
</table>

---

### Evolution of ecological interactions

Ecological interactions are as common as they are varied across species, suggesting that those interactions evolved in response to the changing conditions any lineage experienced.
Although we can directly observe and measure ecological interactions for living species, ancestral interactions are only rarely preserved in the fossil record.
Our work in this area aims to illuminate how ecological interactions evolved within a clade (or between clades) over time by developing phylogenetic models that incorporate empirical and theoretical insights from ecology.

#### Related work

<table>

    <!-- NEW ENTRY -->
    <tr>
        <!-- IMAGE -->
        <td><table table-layout="fixed" style="margin:auto" width="200px">
            <td markdown="span" width="200px">
                <img src="/assets/research/img/Braga_et_al_2021_EcolLett_evol_network.png" style="float: left; margin:0px" height="100" width="200" class="img-circle-5">
            </td>
        </table></td>
        <!-- PAPER -->
        <td><table table-layout="fixed" style="margin:auto">
            <td markdown="span">
                 **MP Braga**, N Janz, S Nylin, F Ronquist, **MJ Landis**. 2021. Phylogenetic reconstruction of ancestral ecological networks through time for pierid butterflies and their host plants. Ecology Letters 24: 2134-2145.<br>
[[paper](/assets/research/pdf/Braga_et_al_2021_EcolLett_evol_network.pdf)] [[scripts](https://github.com/maribraga/evolnets)]
            </td>
        </table></td>
    </tr>

    <!-- NEW ENTRY -->
    <tr>
        <!-- IMAGE -->
        <td><table table-layout="fixed" style="margin:auto" width="200px">
            <td markdown="span" width="200px">
                <img src="/assets/research/img/Landis_et_al_2021_SystBiol_biome_shift.png" style="float: left; margin:0px" height="100" width="200" class="img-circle-5">
            </td>
        </table></td>
        <!-- PAPER -->
        <td><table table-layout="fixed" style="margin:auto">
            <td markdown="span">
                 **MJ Landis**, EJ Edwards, MJ Donoghue. 2021. Modeling phylogenetic biome shifts on a planet with a past. Systematic Biology 70: 86-107.<br>
[[paper](/assets/research/pdf/Landis_et_al_2021_SystBiol_biome_shift.pdf)] [[scripts](https://github.com/mlandis/biome_shift)]
            </td>
        </table></td>
    </tr>

    <tr>
        <!-- IMAGE -->
        <td><table table-layout="fixed" style="margin:auto" width="200px">
            <td markdown="span" width="200px">
                <img src="/assets/research/img/Braga_et_al_2020_SystBiol_host_parasite.png" style="float: left; margin:0px" height="100" width="200" class="img-circle-5">
            </td>
        </table></td>
        <!-- PAPER -->
        <td><table table-layout="fixed" style="margin:auto">
            <td markdown="span">
                 **MP Braga**, **MJ Landis**, S Nylin, N Janz, F Ronquist. 2019. Bayesian inference of ancestral host-parasite interactions under a phylogenetic model of host repertoire evolution. Systematic Biology 69: 1149-1162.<br>
[[paper](/assets/research/pdf/Braga_et_al_2020_SystBiol_host_parasite.pdf)] [[scripts](https://github.com/maribraga/pieridae_hostrep)]
            </td>
        </table></td>
    </tr>
    <tr>
        <!-- IMAGE -->
        <td><table table-layout="fixed" style="margin:auto" width="200px">
            <td markdown="span" width="200px">
                <img src="/assets/research/img/Quintero_Landis_2019_bioRxiv_biotic_interactions.png" style="float: left; margin:0px" height="100" width="200" class="img-circle-5">
            </td>
        </table></td>
        <!-- PAPER -->
        <td><table table-layout="fixed" style="margin:auto">
            <td markdown="span">
                 I Quintero, **MJ Landis** 2019. Interdependent phenotypic and biogeographic evolution driven by biotic interactions. Systematic Biology (accepted).<br>
[[paper](/assets/research/pdf/Quintero_Landis_2019_bioRxiv_biotic_interactions.pdf)]  [[software](https://github.com/ignacioq/Tapestree.jl)]
            </td>
        </table></td>
    </tr>
</table>

---

### Phenotypic evolution

Darwin's original conception of evolution proposed that species evolve gradually over time.
In phylogenetics, this is often modeled as a Brownian motion, whereby small changes occur over many small intervals of time.
Many evolutionary mechanisms, such as rapid adaptation, may produce "pulses" in variation, with punctuated change of large effect.
Rapid change should produce power-law (or heavy-tailed) distributions of traits, but Brownian motion does not generate this feature.
It is difficult to detect these bursts if they are not modeled appropriately.
To search for signals of punctuated evolution, we apply a flexible class of stochastic processes that produce gradual and/or punctuational patterns of change, called Lévy processes.

#### Related work

<table>
    
    <!-- NEW ENTRY -->
    <tr>
        <!-- IMAGE -->
        <td><table table-layout="fixed" style="margin:auto" width="200px">
            <td markdown="span" width="200px">
                <img src="/assets/research/img/Landis_Schraiber_2017_PNAS_pulse_vertebrate.png" style="float: left; margin:0px" height="100" width="200" class="img-circle-5">
            </td>
        </table></td>
        <!-- PAPER -->
        <td><table table-layout="fixed" style="margin:auto">
            <td markdown="span">
                **MJ Landis**, JG Schraiber. 2017. Pulsed evolution shaped modern vertebrate body sizes. Proceedings of the National Academy of Sciences, 114:13224-13229.<br>
                [[paper](/assets/research/pdf/Landis_Schraiber_2017_PNAS_pulse_vertebrate.pdf)]  [[software](http://github.com/Schraiber/pulsR)]
            </td>
        </table></td>
    </tr>
    
    <!-- NEW ENTRY -->
    <tr>
        <!-- IMAGE -->
        <td><table table-layout="fixed" style="margin:auto" width="200px">
            <td markdown="span" width="200px">
                <img src="/assets/research/img/Landis_et_al_2012_SystBiol_phylo_levy.png" style="float: left; margin:0px" height="100" width="200" class="img-circle-5">
            </td>
        </table></td>
        <!-- PAPER -->
        <td><table table-layout="fixed" style="margin:auto">
            <td markdown="span">
                **MJ Landis (\*)**, JG Schraiber (\*), M Liang. 2013. Phylogenetic Analysis Using Lévy Processes: Finding Jumps in the Evolution of Continuous Traits. Systematic Biology, 62:193-204.<br>
                [[paper](/assets/research/pdf/Landis_et_al_2012_SystBiol_phylo_levy.pdf)]  [[software](http://github.com/mlandis/creepy-jerk)]
            </td>
        </table></td>
    </tr>
    
    <!-- NEW ENTRY -->
    <tr>
        <!-- IMAGE -->
        <td><table table-layout="fixed" style="margin:auto" width="200px">
            <td markdown="span" width="200px">
                <img src="/assets/research/img/Schraiber_Landis_2014_TPB_quant_coalescent.png" style="float: left; margin:0px" height="100" width="200" class="img-circle-5">
            </td>
        </table></td>
        <!-- PAPER -->
        <td><table table-layout="fixed" style="margin:auto">
            <td markdown="span">
                JG Schraiber, **MJ Landis**. 2015. Sensitivity of quantitative traits to mutational effects and number of loci. Theoretical Population Biology, 102:85-93.<br>
                [[paper](/assets/research/pdf/Schraiber_Landis_2014_TPB_quant_coalescent.pdf)]  [[scripts](http://github.com/Schraiber/quant_trait_coalescent)]
            </td>
        </table></td>
    </tr>
    
</table>

(\*) - Lead co-authors.



---

### Phylogenetic inference with RevBayes

Learning the degree of relatedness between species has far-reaching implications for biological research, from basic research questions in evolution and ecology, to applied questions in molecular biology, epidemiology, forensics, and biodiversity management.
Inferring phylogeny, ancestral states, and the tempo and mode of evolution ultimately depends on what data is available and how the inference model is designed.
[RevBayes](http://revbayes.com) was designed to allow researchers to tailor models to their needs.
RevBayes achieves this by providing a flexible scripting language to describe probabilistic graphical models.
In general, our work develops new variants of standard stochastic processes -- such as birth-death processes, continuous-time Markov processes, and various jump-diffusion processes -- to test hypotheses for how different groups of species evolved.


#### Related work


<table>
    
    <!-- NEW ENTRY -->
    <tr>
        <!-- IMAGE -->
        <td><table table-layout="fixed" style="margin:auto" width="200px">
            <td markdown="span" width="200px">
                <img src="/assets/research/img/Hoehna_et_al_2016_SystBiol_revbayes.png" style="float: left; margin:0px" height="100" width="200" class="img-circle-5">
            </td>
        </table></td>
        <!-- PAPER -->
        <td><table table-layout="fixed" style="margin:auto">
            <td markdown="span">
                 S Höhna, **MJ Landis**, TA Heath, B Boussau, N Lartillot, BR Moore, JP Huelsenbeck, F Ronquist. 2016. RevBayes: Bayesian Phylogenetic Inference Using Graphical Models and an Interactive Model-Specification Language. Systematic Biology, 65:726-736.<br>
[[paper](/assets/research/pdf/Hoehna_et_al_2016_SystBiol_revbayes.pdf)]  [[software](http://github.com/revbayes/revbayes)]
            </td>
        </table></td>
    </tr>


    <!-- NEW ENTRY -->
    <tr>
        <!-- IMAGE -->
        <td><table table-layout="fixed" style="margin:auto" width="200px">
            <td markdown="span" width="200px">
                <img src="/assets/research/img/Hoehna_et_al_2014_SystBiol_graphical_models.png" style="float: left; margin:0px" height="100" width="200" class="img-circle-5">
            </td>
        </table></td>
        <!-- PAPER -->
        <td><table table-layout="fixed" style="margin:auto">
            <td markdown="span">
                S Höhna, TA Heath, B Boussau, **MJ Landis**, F Ronquist, JP Huelsenbeck. 2014. Probabilistic graphical model representation in phylogenetics. Systematic Biology, 63:753-771.<br>
                [[paper](/assets/research/pdf/Hoehna_et_al_2014_SystBiol_graphical_models.pdf)]
            </td>
        </table></td>
    </tr>
    
    <!-- NEW ENTRY -->
    <tr>
        <!-- IMAGE -->
        <td><table table-layout="fixed" style="margin:auto" width="200px">
            <td markdown="span" width="200px">
                <img src="/assets/research/img/Hoehna_et_al_2017_CurrProcBioinfo_revbayes.png" style="float: left; margin:0px" height="100" width="200" class="img-circle-5">
            </td>
        </table></td>
        <!-- PAPER -->
        <td><table table-layout="fixed" style="margin:auto">
            <td markdown="span">
                S Höhna, **MJ Landis**, TA Heath. 2017. Phylogenetic Inference Using RevBayes. Current Protocols in Bioinformatics, 57:6.16-6.16.34.<br>
[[paper](/assets/research/pdf/Hoehna_et_al_2017_CurrProcBioinfo_revbayes.pdf)]
            </td>
        </table></td>
    </tr>
    
    
    <!-- NEW ENTRY -->
    <tr>
        <!-- IMAGE -->
        <td><table table-layout="fixed" style="margin:auto" width="200px">
            <td markdown="span" width="200px">
                <img src="/assets/research/img/Hoehna_et_al_2021_PeerJ_parallel_marg_like.png" style="float: left; margin:0px" height="100" width="200" class="img-circle-5">
            </td>
        </table></td>
        <!-- PAPER -->
        <td><table table-layout="fixed" style="margin:auto">
            <td markdown="span">
                S Höhna, **MJ Landis**, JP Huelsenbeck. 2021. Parallel power posterior analyses for fast computation of marginal likelihoods in phylogenetics. PeerJ 9:e12438.<br>
                [[paper](/assets/research/pdf/Hoehna_et_al_2021_PeerJ_parallel_marg_like.pdf)]
            </td>
        </table></td>
    </tr>
    

</table>
