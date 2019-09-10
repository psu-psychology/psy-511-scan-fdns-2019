---
title: "Methods in Cognitive and Affective Neuroscience"
author: "Rick Gilmore"
date: "2019-09-10 16:04:40"
bibliography: bib/bibliography.bib
csl: bib/apa.csl
output:
  html_document:
    keep_md: true
    theme: spacelab
    toc: yes
    toc_depth: 3
    toc_float: no
    code_folding: hide
  ioslides_presentation:
    self_contained: false
    lib_dir: libs
    widescreen: true
    incremental: false
    transition: default
  pdf_document:
    toc: true
    toc_depth: 1
    keep_tex: true
    latex_engine: lualatex
    fig_width: 7
    fig_height: 6
---

<style type="text/css">
body { font-size: 18px; max-width: 1800px; margin: auto; padding: 1em; }
code.r { font-size: 20px; }
pre { font-size: 16px; }
p { padding-top: 10px; padding-bottom: 4px; }
h1 { font-size: 28px; }
h2 { font-size: 25px; }
h3 { font-size: 21px; }
li { font-size: 18px; }
.center_video { object-position: center center;}
</style>



# Evaluating methods 

## What are we measuring?

- Structure
- Activity
    - Why not *function*?

## What is question are we asking?

- Structure X -> Structure Y
- Structure X -> Function Y

## Strengths & Weaknesses

- Cost
- Invasiveness
- Spatial/temporal resolution

## Spatial resolution

<img src="img/churchland-levels-of-analysis.gif" width="800px" style="display: block; margin: auto;" />

## Temporal resolution

<img src="https://media.nature.com/lw926/nature-assets/neuro/journal/v17/n11/images/nn.3839-F1.jpg" width="800px" style="display: block; margin: auto;" />

[[@Sejnowski2014-aa]](https://doi.org/10.1038/nn.3839)

## Types

- Structural
  - Anatomy
  - Connectivity/connectome
- Activity/Functional
  - What does it do?
  - Physiology

# Structural methods

## Cellular

- Cell/axon stains
- Cellular types, distribution, concentration, microanatomy
- Connectivity

### Golgi stain -- whole cells, but small %

<img src="img/golgi-stain.jpg" width="800px" style="display: block; margin: auto;" />
<https://connectomethebook.com/wp-content/uploads/2011/11/Brainforest17_1119.jpg>

<img src="https://www.hitobiotec.com/media/catalog/product/cache/1/image/9df78eab33525d08d6e5fb8d27136e95/h/i/hito_golgi_staining_10.jpg" width="800px" style="display: block; margin: auto;" />

<img src="https://wam.umn.edu/wp-content/uploads/2016/12/WAM_Cajal_m1673.jpg" width="800px" style="display: block; margin: auto;" />
<https://wam.umn.edu/calendar/cajal/>

**Camillo Golgi**

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5f/Camillo_Golgi.jpg/330px-Camillo_Golgi.jpg" width="800px" style="display: block; margin: auto;" />
<https://en.wikipedia.org/wiki/Camillo_Golgi>

### Nissl stain -- only cell bodies

<img src="https://i.pinimg.com/originals/24/ba/58/24ba5870a0b3ac2ce8e3620853e12c8b.jpg" width="800px" style="display: block; margin: auto;" />

**[Franz Nissl](https://en.wikipedia.org/wiki/Franz_Nissl)**

<img src="https://upload.wikimedia.org/wikipedia/commons/d/dd/Portrait_of_Franz_Nissl.jpg" width="800px" style="display: block; margin: auto;" />

### [Brainbow](https://cbs.fas.harvard.edu/science/connectome-project/brainbow)

<img src="img/lichtman-nrn2391-f1.jpg" width="800px" style="display: block; margin: auto;" />
[[@lichtman_technicolour_2008]](https://doi.org/10.1038/nrn2391)

<img src="img/lichtman-nrn2391-f2.jpg" width="800px" style="display: block; margin: auto;" />
[[@lichtman_technicolour_2008]](https://doi.org/10.1038/nrn2391)

### Clarity

<iframe width="560" height="315" src="https://www.youtube.com/embed/c-NMfp13Uug" frameborder="0" allowfullscreen></iframe>

<https://clarityresourcecenter.com/CLARITY.html>

### Tracers

- Retrograde (output -> input)
- Anterograde (input -> output)

<img src="img/retrograde-anterograde-tracers.png" width="800px" style="display: block; margin: auto;" />
<https://openi.nlm.nih.gov/imgs/512/348/3176268/3176268_1471-2105-12-351-2.png>

<iframe width="560" height="315" src="https://www.youtube.com/embed/nvXuq9jRWKE" frameborder="0" allowfullscreen></iframe>

### Evaluating cellular techniques

- Invasive (in humans post-mortem only)
- High *spatial* resolution, but poor/coarse *temporal*
    - Why?

## Mapping large-scale structures

### Computed axial tomography (CAT), CT

- Computed Tomography (CT)
- X-ray based

<img src="img/tomography.png" width="800px" style="display: block; margin: auto;" />
<https://img.tfd.com/mk/T/X2604-T-22.png>

**Tomography**

<img src="img/cat-scan-pineapple.jpg" width="800px" style="display: block; margin: auto;" />
<https://static.howstuffworks.com/gif/cat-scan-pineapple.jpg>

<img src="https://miro.medium.com/max/1024/1*j09PgBpdJIHXhlyjcby0HA.jpeg" width="800px" style="display: block; margin: auto;" />

<https://medium.com/datadriveninvestor/detecting-brain-hemorrhage-in-computed-tomography-ct-imaging-d1276cb6bdb7>

### Magnetic Resonance Imaging (MRI)

- Magnetic resonance a property of some isotopes and complex molecules
- Hydrogen ($H$), common in water & fat, is one
- In magnetic field, $H$ atoms absorb and release radio frequency (RF) energy
- $H$ atoms align with strong magnetic field

<img src="img/mri-steps.jpg" width="800px" style="display: block; margin: auto;" />

<https://s.hswstatic.com/gif/mri-steps.jpg>

- Applying RF pulse perturbs alignment
- Rate/timing of realignment varies by tissue
- Realignment gives off radio frequency (RF) signals
- Strength of RF ~ density of $H$ (or other target)
- K-space (frequency/phase) -> anatomical space

**Structural MRI**

- Tissue density/type differences
- **Gray matter** (nerve cells & **dendrites**) vs. **white matter** (**axon fibers**)
- Region sizes/volumes

<img src="https://previews.123rf.com/images/ultimagaina/ultimagaina1405/ultimagaina140500005/28078449-Sequence-of-vertical-sections-of-a-human-brain-MRI-scan-Stock-Photo.jpg" width="800px" style="display: block; margin: auto;" />

**Spectroscopy** (specific metabolites)

<img src="https://images.radiopaedia.org/images/556479/0dc08a48892084b4c3b717feb9dfa4_big_gallery.jpg" width="800px" height="550px" style="display: block; margin: auto;" />

**Voxel-based morphometry (VBM)**

- Quantitative analyses of size/volume
- Example: volume differences in schizophrenic patients vs. controls using statistical maps of size differences

<img src="https://openi.nlm.nih.gov/imgs/512/130/2927029/PMC2927029_mp2009146f1.png" width="800px" style="display: block; margin: auto;" />
[[@Pomarol-Clotet2010-tq]](https://dx.doi.org/10.1038/mp.2009.146)

**Diffusion Tensor Imaging (DTI)**

- Structural MRI technique
- Diffusion tensor: measurement of spatial pattern of $H_2O$ diffusion in small volume
- Uniform ("isotropic") vs. non-uniform ("anisotropic")
- Strong anisotropy suggests large # of axons with similar orientations (fiber tracts)

<img src="https://1.bp.blogspot.com/-YO3h0cRqTEc/UIRKEC_0N8I/AAAAAAAABQs/dEPzCbcyuCo/s1600/FA_tensor.png" width="700px" style="display: block; margin: auto;" />

- Fractional Anisotropy (FA), radial diffusivity (RD), mean diffusivity (MD) measures of "non-uniformity" of diffusion tensor
- Connecting tensors or fiber tract tracing

<img src="https://4.bp.blogspot.com/-j3_rRdZXx0Q/VQXD0vGD8uI/AAAAAAAACr0/MYTD4MhC8rY/s1600/tractography_2014%2Bcopy.png" width="800px" style="display: block; margin: auto;" />

<img src="https://www.nap.edu/openbook/13373/xhtml/images/p26.jpg" width="800px" style="display: block; margin: auto;" />

### Connectome

- What is the wiring diagram?

<img src="https://journals.plos.org/plosone/article/figure/image?size=large&download=&id=10.1371/journal.pone.0135247.g002" width="800px" style="display: block; margin: auto;" />

<img src="https://www.humanconnectome.org/storage/app/media/news/2015/09/CCA_mode.jpg" width="800px" style="display: block; margin: auto;" />

# Functional (activity) methods

- Recording from the brain 
- Interfering with the brain 
- Stimulating the brain
- Simulating the brain

## ￼Recording from the brain
### Single/multi unit recording

- Microelectrodes
- Small numbers of nerve cells

<img src="img/multi-unit-recording.jpg" width="600px" style="display: block; margin: auto;" />

<https://www.nature.com/nrn/journal/v5/n11/images/nrn1535-i1.jpg>

- What does neuron X respond to?
- High temporal (ms) + spatial resolution (um)
- Invasive
- Rarely suitable for humans, but...

**Electrocorticography (ECoG)****

<img src="https://www.neurofisiologia.net/wp-content/uploads/2009/07/corticografia.jpg" width="800px" style="display: block; margin: auto;" />

<iframe width="560" height="315" src="https://www.youtube.com/embed/HluVToAamXY" frameborder="0" allowfullscreen></iframe>
</div>

**Single-cell studies ask...**

- How does firing frequency, timing vary with behavior?

### Positron Emission Tomography (PET)

<iframe width="560" height="315" src="https://www.youtube.com/embed/GHLBcCv4rqk" frameborder="0" allowfullscreen></iframe>

- Radioactive tracers (glucose, oxygen)
- Positron decay activates paired detectors
- Tomographic techniques reconstruct 3D geometry
- Experimental condition - control
- Average across individuals
- Temporal (~ s) and spatial (mm-cm) resolution worse than fMRI
- Radioactive exposures + mildly invasive 
- Dose < airline crew exposure in 1 yr

### Functional Magnetic Resonance Imaging (fMRI)

- Neural activity -> local $O_2$ consumption increase
- *Blood Oxygen Level Dependent (BOLD)* response
- Oxygenated vs. deoxygenated hemoglobin ≠ magnetic susceptibility

- How do regional blood $O_2$ levels (& flow & volume) vary with behavior X?
- MRI "signals" relate to the speed (1/T) of "relaxation" of the perturbed nuclei to their state of alignment with the main ($B_0$) magnetic field.
- Imaging protocols emphasize different time constants of this relaxation ($T^1$, $T^2$, $T^{2*}$); $T^{2*}$ for BOLD imaging

**Evaluating fMRI**

- Non-invasive, but expensive
- Moderate but improving (mm) spatial, temporal (~sec) resolution
- Spatial limits due to 
    - field strength (@ 3T $~3mm^3$ voxel)
    - Physiology of hemodynamic response
- Temporal limits due to
    - Hemodynamic Response Function (HRF): ~ 1s delay plus 3-6 s ramp-up
    - Speed of image acquisition ($TR$ is time of image acquisition, usually 2-3s for whole brain studies)
- *Indirect* measure of neural activity

**Hemodynamic Response Function (HRF)**

<img src="img/hemodynamic-response-function.png" width="800px" style="display: block; margin: auto;" />

**Typical analysis...**

Generate "predicted" BOLD response to event; compare to actual

<img src="https://mriquestions.com/uploads/3/4/5/7/34572113/convolution-of-3-events_orig.gif" width="800px" style="display: block; margin: auto;" />

Average across individual participants and plot statistical maps (in color space) on top of structural image.

<img src="https://upload.wikimedia.org/wikipedia/commons/8/87/Functional_magnetic_resonance_imaging.jpg" width="800px" style="display: block; margin: auto;" />
<https://en.wikibooks.org/wiki/Cognitive_Psychology_and_Cognitive_Neuroscience/Behavioural_and_Neuroscience_Methods#fMRI>

**Effects of higher field strengths (3 Tesla vs. 7 Tesla)**

<img src="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3629563/bin/gr3.jpg" width="800px" height="450px" style="display: block; margin: auto;" />
[[@Sladky2013-bu]](https://dx.doi.org/10.1016/j.ejrad.2011.09.025)
</div>

### Functional Near-infrared Spectroscopy (fNIRS or NIRS)

- Near infrared light penetrates scalp and skull, refracted by brain tissue
- Returned signal altered by blood $O_2$ levels
- Time course (temporal resolution) ~ BOLD fMRI; spatial resolution low

<div class="figure" style="text-align: center">
<img src="https://cibsr.stanford.edu/NIRS_Lab/_jcr_content/main/panel_builder/panel_0/image.img.full.high.png" alt="Source: https://cibsr.stanford.edu/NIRS_Lab.html" width="700px" />
<p class="caption">Source: https://cibsr.stanford.edu/NIRS_Lab.html</p>
</div>

<div class="figure" style="text-align: center">
<img src="https://images.squarespace-cdn.com/content/v1/54e7b27de4b0b080e1552803/1557982253763-E0WULBZB7PQBS124L7JG/ke17ZwdGBToddI8pDm48kNNnzL9xRi0AnU-1PeZqRnNZw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZamWLI2zvYWH8K3-s_4yszcp2ryTI0HqTOaaUohrI8PIN3GI4mGL6orgGNgjoMp7j5NF-bk__8b8xi11mt0OJKgKMshLAGzx4R3EDFOm1kBS/fNIRS-EEG+closeup+side+-+large.jpg?format=500w" alt="Source: https://nirx.net" width="600px" />
<p class="caption">Source: https://nirx.net</p>
</div>

### Electroencephalography (EEG)

<img src="https://ars.els-cdn.com/content/image/1-s2.0-S0166223617300243-gr1_lrg.jpg" width="800px" style="display: block; margin: auto;" />
[[@Cohen2017-og]](https://dx.doi.org/10.1016/j.tins.2017.02.004)

- How does it work?
- Electrodes on scalp or brain surface
- What do we measure?
    - Voltage *differences* between source and reference electrode
- Combined activity of huge # of neurons
- Thought to arise from current/voltage gradients between *apical* (near surface) dendrites and *basal* (deeper) dendrites and cell body/soma

<img src="https://neurofeedbackalliance.org/wp-content/uploads/2016/10/Dipole.jpg" width="800px" style="display: block; margin: auto;" />

<img src="img/baby-eeg.jpg" width="600px" style="display: block; margin: auto;" />
<https://sfari.org/images/images-2013-folder/images-sfn-2013/20131110sfneeg>

- High temporal, poor spatial resolution
- Analyze activity in different 'bands' of frequencies
    + LOW: deep sleep (delta or $\delta$ band)
    + MIDDLE: Quiet, alert state (alpha $\alpha$ band)
    + HIGHER: Sensorimotor activity reflecting observed actions? (mu or $\mu$ band), [[@Hobson2017-oj]](https://dx.doi.org/10.1098/rsos.160662)
    + HIGHER STILL: “Binding” information across senses or plasticity? (gamma or $\gamma$ band), [[@Amo2017-tz]](https://dx.doi.org/10.1371/journal.pone.0186008)
  
**Analyze in frequency domains**

<img src="img/eeg-frequency.jpg" width="650px" style="display: block; margin: auto;" />
<https://www.peakmind.co.uk/images/frequency.jpg>

<img src="https://ars.els-cdn.com/content/image/1-s2.0-S0166223617300243-gr2_lrg.jpg" width="800px" style="display: block; margin: auto;" />
[[@Cohen2017-og]](https://dx.doi.org/10.1016/j.tins.2017.02.004)

**Event-related potentials (ERPs)**

- EEGs time-locked to some event 
- ...Averaged over many such events (trials)

<img src="https://2.bp.blogspot.com/_2ob-1_LsjJs/TAUjw9i_dYI/AAAAAAAAAQQ/9AfiHsnD-P8/s1600/ERP_technique.gif" width="700px" style="display: block; margin: auto;" />

**Brain Computer Interface (BCI)**

- May rely on EEG/ERP or electrocorticographic methods

<img src="https://s.hswstatic.com/gif/brain-computer-interface-3.gif" width="800px" height="500px" style="display: block; margin: auto;" />
<https://s.hswstatic.com/gif/brain-computer-interface-3.gif>

### Magneto-encephalography (MEG)

- Like EEG, but measuring magnetic fields
- High temporal resolution
- Magnetic fields propagate w/o distortion
    - But are orthogonal to electric field
- Requires shielded chamber (to keep out strong magnetic fields)
- ++ cost vs. EEG

<img src="https://www.massgeneral.org/psychiatry/assets/images/Magnetoencephalography_MEG_MGH.jpg" width="800px" style="display: block; margin: auto;" />

### How do EEG/MEG and fMRI relate? {.flexbox .vcenter}

<img src="img/logothetis-2001.jpg" width="650px" style="display: block; margin: auto;" />

[[@Logothetis2001-ul]](https://doi.org/10.1038/35084005)
</div>

- BOLD fMRI likely reflects **presynaptic** *input* to area
- EEG/MEG likely reflects **postsynaptic** *response* to those inputs
- [[@Logothetis2001-ul]](https://doi.org/10.1038/35084005) and [[@Logothetis2004-mn]](https://doi.org/10.1146/annurev.physiol.66.082602.092845)

## Manipulating the brain

- Interfering with it 
- Stimulating it

### Interfering with the brain

- Nature’s “experiments” 
- Stroke, head injury, tumor
- Neuropsychology

**Galen**

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/80/Galenus.jpg/330px-Galenus.jpg" width="800px" style="display: block; margin: auto;" />
<https://en.wikipedia.org/wiki/Galen>

**Phineas Gage**

<img src="https://www.wshu.org/sites/wshu/files/styles/x_large/public/201710/Phineas3.jpg" width="800px" height="500px" style="display: block; margin: auto;" />

I highly recommend the work of the late Oliver Sacks.

<img src="https://upload.wikimedia.org/wikipedia/en/9/98/The_Man_Who_Mistook_His_Wife_for_a_Hat_cover.jpg" width="800px" height="550px" style="display: block; margin: auto;" />

- Logic: IF damage to area X impairs performance, THEN region critical for behavior Y
- *Double dissociation*: Damage to area Z leaves behavior Y intact
- Weak spatial/temporal resolution

### ￼Stimulating the brain

- Electrical (**Direct Current Stimulation - DCS**)

<img src="https://upload.wikimedia.org/wikipedia/commons/d/df/TDCS_administration.gif" width="800px" style="display: block; margin: auto;" />
<https://en.wikipedia.org/wiki/Transcranial_direct-current_stimulation>

- Pharmacological
- Magnetic (**Transcranial magnetic stimulation - TMS**)

<img src="https://upload.wikimedia.org/wikipedia/commons/6/67/Transcranial_magnetic_stimulation.jpg" width="800px" style="display: block; margin: auto;" />
<https://en.wikipedia.org/wiki/Transcranial_magnetic_stimulation>

- Spatial/temporal resolution?
- Assume stimulation mimics natural activity?

**Deep brain electrical stimulation as therapy for...**

- Depression 
- Epilepsy
- Parkinson’s Disease 

<img src="img/deep-brain-stimulation.jpg" width="700px" style="display: block; margin: auto;" />
<https://www.nimh.nih.gov/images/health-and-outreach/mental-health-topic-brain-stimulation-therapies/dbs_60715_3.jpg>

<iframe width="560" height="315" src="https://www.youtube.com/embed/KDjWdtDyz5I" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
<https://youtu.be/KDjWdtDyz5I>

**Optogenetics**

<iframe width="560" height="315" src="https://www.youtube.com/embed/I64X7vHSHOE" frameborder="0" allowfullscreen></iframe>
<https://www.youtube.com/I64X7vHSHOE>

- Gene splicing techniques insert light-sensitive molecules into neuronal membranes
- Application of light at specific wavelengths alters neuronal function
- Cell-type specific and temporally precise control
- Mimics brain activity
- <https://en.wikipedia.org/wiki/Optogenetics>

<iframe width="560" height="315" src="https://www.youtube.com/embed/FlGbznBmx8M" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
<https://youtu.be/FlGbznBmx8M>

## *Sim*ulating the brain

- Computer/mathematical models of brain function
- Example: neural networks
- Cheap, noninvasive, can be stimulated or “lesioned”

**Blue Brain project**

<img src="https://www.nature.com/nrn/journal/v7/n2/images/nrn1848-f4.jpg" width="600px" style="display: block; margin: auto;" />
[Markram, 2006](https://doi.org/10.1038/nrn1848)

Or, here's an example of a brain-like use of artificial intelligence.

<iframe width="560" height="315" src="https://www.youtube.com/embed/gn4nRCC9TwQ" frameborder="0" allowfullscreen></iframe>

**Hodgkin-Huxley model of the action potential**

Computational neuroscience really began with a set of mathematical models of how neurons generate and send electrical messages down the axon [[@Hodgkin1952-so]](https://dx.doi.org/10.1113/jphysiol.1952.sp004764).
The graphs below simulate the time course of voltage $v$ several difference types of conductance (flow of electrical current) thought to mimic what goes on in an actual neuron.
Thanks to <https://magesblog.com/post/2012-06-25-hodgkin-huxley-model-in-r/> for the code.



<img src="imgunnamed-chunk-49-1.png" width="800px" style="display: block; margin: auto;" />

## Measuring the body

- Psychophysiological measures (heart rate, respiration rate, skin conductance or electrodermal activity)
- Body position measures (eye/gaze tracking, motion tracking, electromyography or EMG)
- Endocrine (hormonal) measures

# References {.smaller}
