---
title: "511-anatomy-outline"
author: "Rick Gilmore"
date: "2019-09-10 13:11:11"
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
body{ font-size: 18px; max-width: 1800px; margin: auto; padding: 1em; }
code.r{ font-size: 20px; }
pre { font-size: 16px; }
p { padding-top: 10px; padding-bottom: 4px; }
h1 { font-size: 28px; }
h2 { font-size: 25px; }
h3 { font-size: 21px; }
.center_video { object-position: center center;}
</style>



---

# Fun

<div class="center_video">
<iframe width="560" height="315" src="https://www.youtube.com/embed/snO68aJTOpM" frameborder="0" allowfullscreen></iframe>
</div>

<https://www.youtube.com/snO68aJTOpM>
<!-- Pinky and the Brain video -->

<iframe width="560" height="315" src="https://www.youtube.com/embed/Qw8E9WnZTQk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<!-- Kids brain song -->

# Resources

## Harvard Brain Atlas

<div class="figure" style="text-align: center">
<iframe src="http://www.med.harvard.edu/aanlib/cases/caseNA/pb9.htm" width="800px" height="400px"></iframe>
<p class="caption">http://www.med.harvard.edu/aanlib/cases/caseNA/pb9.htm</p>
</div>

# Directional terms

- Anterior/Posterior
- Medial/Lateral
- Superior/Inferior
- Dorsal/Ventral
- Rostral/Caudal

<audio controls loop="loop">
  <source src="snd/brain_boxing.m4a" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Blausen_0019_AnatomicalDirectionalReferences.png/800px-Blausen_0019_AnatomicalDirectionalReferences.png" width="800px" style="display: block; margin: auto;" />

**Bipeds vs. quadripeds**

<div class="figure" style="text-align: center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/00/1303_Human_Neuroaxis.jpg/800px-1303_Human_Neuroaxis.jpg" alt="https://upload.wikimedia.org/wikipedia/commons/thumb/0/00/1303_Human_Neuroaxis.jpg/800px-1303_Human_Neuroaxis.jpg" width="800px" />
<p class="caption">https://upload.wikimedia.org/wikipedia/commons/thumb/0/00/1303_Human_Neuroaxis.jpg/800px-1303_Human_Neuroaxis.jpg</p>
</div>

## Image axes

- Horizontal/Axial
- Coronal/Transverse/Frontal
- Sagittal (from the side)

<div class="figure" style="text-align: center">
<img src="http://www.scienceteacherprogram.org/biology/chillemistudentguide1-06/brain_directions_planes_sections__directions_-_small.gif" alt="http://www.scienceteacherprogram.org/biology/chillemistudentguide1-06/brain_directions_planes_sections__directions_-_small.gif" width="800px" />
<p class="caption">http://www.scienceteacherprogram.org/biology/chillemistudentguide1-06/brain_directions_planes_sections__directions_-_small.gif</p>
</div>

# Supporting structures
## Meninges

- Dura mater ('tough mother')
- Arachnoid membrane
- Subarachnoid space
- Pia mater ('gentle mother')

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8e/Meninges-en.svg/1280px-Meninges-en.svg.png" width="800px" style="display: block; margin: auto;" />

## Ventricular system (Cerebral ventricles)

- Lateral (1st & 2nd)
- 3rd
- Cerebral aqueduct 
- 4th

<img src="https://upload.wikimedia.org/wikipedia/commons/d/d4/Blausen_0896_Ventricles_Brain.png" width="800px" style="display: block; margin: auto;" />

- Ventricles filled with cerebrospinal fluid (CSF)
  - CSF clears metabolites during sleep [@xie2013sleep]?

## Blood Supply

- Carotid & vertebral arteries converge on Circle of Willis
- Anterior, Middle, and Posterior Cerebral arteries main output

<img src="http://surgery.med.miami.edu/images/Circulation_of_brain.gif" width="800px" style="display: block; margin: auto;" />

### Blood/brain barrier

- Cells forming blood vessel walls tightly packed
- Active transport of molecules typically required

<img src="http://www.nature.com/nrn/journal/v7/n1/images/nrn1824-f3.jpg" width="800px" style="display: block; margin: auto;" />

**Area Postrema**

- In brainstem, blood-brain barrier thin
- Chemoreceptors detect toxins, trigger emesis if necessary

<img src="http://www.nature.com/nrendo/journal/v9/n10/images/nrendo.2013.136-f2.jpg" width="800px" style="display: block; margin: auto;" />

# Organization of the Nervous System

<div class="figure" style="text-align: center">
<img src="https://www.pastmedicalhistory.co.uk/wp-content/uploads/2018/08/A-model-of-the-human-nervous-system-by-Rufus-Benjamin-Weaver..jpg" alt="https://www.pastmedicalhistory.co.uk/the-nervous-system-of-harriet-cole/" width="800px" />
<p class="caption">https://www.pastmedicalhistory.co.uk/the-nervous-system-of-harriet-cole/</p>
</div>

- Central Nervous System (CNS) 
  - Brain
  - Spinal Cord
  - (Everything encased in bone)
- Peripheral Nervous System (PNS)

# Organization of the CNS

| Major division | Ventricular Landmark | Embryonic Division | Structure       |
|----------------|----------------------|--------------------|-----------------|
| Forebrain      | Lateral              | Telencephalon      | Cerebral cortex |
|                |                      |                    | Basal ganglia   |
|                |                      |                    | Hippocampus, amygdala |
|                | Third                | Diencephalon       | Thalamus        |
|                |                      |                    | Hypothalamus    |
| Midbrain       | Cerebral Aqueduct    | Mesencephalon      | Tectum, tegmentum |
| Hindbrain      | 4th                  | Metencephalon      | Cerebellum, pons  |
|                | --                   | Mylencephalon      | Medulla oblongata |

- Forebrain, midbrain, hindbrain terminology derives from embryonic stages in CNS development.

## Hindbrain

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/54/EmbryonicBrain.svg/1200px-EmbryonicBrain.svg.png" width="800px" style="display: block; margin: auto;" />

- Hindbrain: structures adjacent (or caudal to) 4th ventricle
    - Medulla oblongata
    - Cerebellum
    - Pons

<div class="centered">
<iframe width="560" height="315" src="https://www.youtube.com/embed/Wq8EVQUc9a4" frameborder="0" allowfullscreen></iframe>
</div>

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b9/Gray708.svg/500px-Gray708.svg.png" width="800px" style="display: block; margin: auto;" />

<img src="http://webspace.ship.edu/cgboer/medial-labelled.gif" width="800px" style="display: block; margin: auto;" />

### [Medulla oblongata](https://en.wikipedia.org/wiki/Medulla_oblongata) {.smaller}

- Cardiovascular regulation
- Muscle tone
- Fibers of passage
    - Ascending fibers (from body), a.k.a. afferents
    - Descending fibers (**e**xiting brain), a.k.a., **e**fferents

<img src="https://upload.wikimedia.org/wikipedia/commons/6/69/1311_Brain_Stem.jpg" width="800px" style="display: block; margin: auto;" />

### Cerebellum

- “Little brain”
- Dorsal to pons
- Movement coordination, simple learning

<img src="https://upload.wikimedia.org/wikipedia/commons/1/14/Cerebellum_animation_small.gif" width="800px" style="display: block; margin: auto;" />

<div class="centered">
<iframe width="560" height="315" src="https://www.youtube.com/embed/6szEeD0n-oU" frameborder="0" allowfullscreen></iframe>
</div>

### Pons

- Bulge on brain stem
- Neuromodulatory nuclei (e.g., 5-HT, NE, ACh, DA)
- Relay to cerebellum

## Midbrain

- Tectum (roof), dorsal
- Tegmentum (floor), ventral

<img src="http://antranik.org/wp-content/uploads/2011/11/the-brain-stem-mid-brain-left-lateral-view-superior-colliculus-inferior-cerebellar-peduncle.jpg" width="800px" style="display: block; margin: auto;" />

### Tectum

- "Roof" of the midbrain
- Superior and inferior colliculus (colliculi is plural)
- Reflexive orienting of eyes, head, ears

<img src="https://upload.wikimedia.org/wikipedia/commons/0/0b/Gray719.png" width="800px" style="display: block; margin: auto;" />

<img src="http://www.radioanatomie.com/30_irm_sagittale_mediane/99_images/2_Tectum.jpg" width="800px" style="display: block; margin: auto;" />

### Tegmentum

- "Floor" of the midbrain
- Species-typical movement sequences
- Neuromodulatory nuclei
    + Norepinephrine (NE)
    + Serotonin (5-HT)
    + Dopamine (DA) -- from *ventral tegmental area (VTA)*

<img src="https://vignette1.wikia.nocookie.net/addictionpathology/images/8/8b/The_reward_pathway_2.gif/revision/latest?cb=20091210025108" width="800px" style="display: block; margin: auto;" />

## Forebrain

- Diencephalon
- Telencephalon

<img src="http://classconnection.s3.amazonaws.com/252/flashcards/1048252/png/forebrain1328987872235.png" width="800px" style="display: block; margin: auto;" />

### Diencephalon

- Thalamus
- Hypothalamus

<img src="https://upload.wikimedia.org/wikipedia/commons/a/a0/1310_Diencephalon.jpg" width="800px" style="display: block; margin: auto;" />

<img src="http://webspace.ship.edu/cgboer/medial-labelled.gif" width="800px" style="display: block; margin: auto;" />

#### Thalamus

- Input to cortex
- Functionally distinct *nuclei* (collection of neurons)
    - Lateral geniculate nucleus (LGN), vision
    - Medial geniculate nucleus (MGN), audition
    - Pulvinar, attention?
  
<img src="http://neurobiologychapter3.weebly.com/uploads/1/4/1/8/1418733/5118342.jpg?401x231" width="800px" style="display: block; margin: auto;" />

#### Hypothalamus

- Five Fs: fighting, fleeing/freezing, feeding, and reproduction
- Controls pituitary gland (“master” gland)
    + Anterior pituitary (indirect release of hormones)
        * e.g., Corticotropin Releasing Hormone (CRH) -> release of cortisol from Adrenal Cortex
    + Posterior pituitary (direct release of hormones)
        * Oxytocin
	      * Vasopressin (aka, Arginine Vasopressin -- AVP; Anti-diuretic Hormone -- ADH)

<img src="http://higheredbcs.wiley.com/legacy/college/tortora/0470565101/hearthis_ill/pap13e_ch14_illustr_audio_mp3_am/simulations/figures/hypothalamus.jpg" width="800px" style="display: block; margin: auto;" />

<!-- Pituitary -->
<img src="https://i.stack.imgur.com/IeFkI.jpg" width="800px" style="display: block; margin: auto;" />

### Telencephalon

- Basal ganglia
- Hippocampus, amygdala
- Cerebral cortex

#### Basal Ganglia

- Skill and habit learning
- Linked to Tourette syndrome, obsessive-compulsive disorder (OCD), addiction, movement disorders
- Example: Parkinson's Disease

<img src="http://webspace.ship.edu/cgboer/basalgangliagray.gif" width="800px" style="display: block; margin: auto;" />


- Striatum
	- Caudate nucleus 
	- Putamen
- Globus pallidus
- Subthalamic nucleus 
- Substantia nigra (tegmentum)

<!-- MRI of basal ganglia -->
<img src="https://fhs122anatomyelab.files.wordpress.com/2014/05/basal-ganglia.jpg?w=524&h=393" width="800px" style="display: block; margin: auto;" />

<div class="centered">
<iframe width="560" height="315" src="https://www.youtube.com/embed/q7z-373pwuI" frameborder="0" allowfullscreen></iframe>
</div>

#### Hippocampus

- Medial to lateral ventricles
- Memories of specific facts or events; place memory in non-human animals
- Fornix projects to (mammillary bodies of) hypothalamus

<img src="http://homepage.smc.edu/wissmann_paul/physnet/anatomynet/anatomy/amy.jpg" width="800px" style="display: block; margin: auto;" />

<img src="http://www.neuro24.de/hip0006.jpg" width="800px" style="display: block; margin: auto;" />

<div class="centered">
<iframe width="560" height="315" src="https://www.youtube.com/embed/wjvDDH-uJ0s" frameborder="0" allowfullscreen></iframe>
</div>

#### Amygdala (“almond”)

- Physiological state, behavioral readiness, affect
- NOT the fear center! [@ledoux_amygdala_2015].

<img src="http://homepage.smc.edu/wissmann_paul/physnet/anatomynet/anatomy/amy.jpg" width="800px" style="display: block; margin: auto;" />

<img src="http://www.frontiersin.org/files/Articles/31697/fpsyg-03-00319-HTML/image_m/fpsyg-03-00319-g002.jpg" width="800px" style="display: block; margin: auto;" />

<div class="centered">
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB9rs4tEAaE" frameborder="0" allowfullscreen></iframe>
</div>

#### Cerebral Cortex 

- Cerebral hemispheres
- Groove (sulcus or sulci)
- Bumps (gyrus or gyri)
- Grey vs. white matter
- Lobes

**Lateral view**

<img src="https://upload.wikimedia.org/wikipedia/commons/3/35/Gray726.png" width="800px" style="display: block; margin: auto;" />

**Medial view**

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fe/Gray727.svg/1025px-Gray727.svg.png" width="800px" style="display: block; margin: auto;" />

**Nissl stain**

<img src="https://upload.wikimedia.org/wikipedia/commons/9/9a/Brainmaps-macaque-hippocampus.jpg" width="800px" style="display: block; margin: auto;" />

###### Lobes of the cerebral cortex

- Frontal
- Temporal
- Parietal
- Occipital
- Names derive from bones of the skull

<img src="https://en.wikipedia.org/wiki/Skull" width="800px" style="display: block; margin: auto;" />

<img src="http://40.media.tumblr.com/tumblr_m1kpkr7Wsq1rn6pqko1_500.jpg" width="800px" style="display: block; margin: auto;" />

**Longitudinal fissure**

<img src="https://upload.wikimedia.org/wikipedia/commons/0/04/Human_brain_longitudinal_fissure.png" width="800px" style="display: block; margin: auto;" />

**Lateral sulcus/fissure**

<img src="https://upload.wikimedia.org/wikipedia/commons/4/41/Lateral_sulcus2.png" width="800px" style="display: block; margin: auto;" />

**Central sulcus**

<img src="https://upload.wikimedia.org/wikipedia/commons/8/88/Central_sulcus_diagram.png" width="800px" style="display: block; margin: auto;" />

###### Frontal lobe

- Anterior to central sulcus
- Superior to lateral fissure
- Dorsal to temporal lobe

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0e/Lobes_of_the_brain_NL.svg/1024px-Lobes_of_the_brain_NL.svg.png" width="800px" style="display: block; margin: auto;" />

- Primary motor cortex (M1) 
    + Supplementary motor cortex
    + Frontal eye fields (FEF)
- Prefrontal cortex
    + Planning, problem solving, working memory...?
- Basal forebrain
    + [Nucleus accumbens (NAcc)](https://en.wikipedia.org/wiki/Nucleus_accumbens), part of ventral striatum
- [Anterior cingulate cortex (ACC)](https://en.wikipedia.org/wiki/Anterior_cingulate_cortex)
- Primary olfactory cortex

<img src="http://cis.jhu.edu/data.sets/cortical_segmentation_validation/photos/cinggyrus75.jpg" width="800px" style="display: block; margin: auto;" />

**Inferior Frontal Gyrus (IFG)**

<img src="https://upload.wikimedia.org/wikipedia/commons/b/b2/Gray726_inferior_frontal_gyrus.png" width="800px" style="display: block; margin: auto;" />

**Middle Frontal Gyrus (MFG)**

<img src="https://upload.wikimedia.org/wikipedia/commons/7/7f/Gray726_middle_frontal_gyrus.png" width="800px" style="display: block; margin: auto;" />

###### Temporal lobe 

- Ventral to frontal, parietal lobes
- Inferior to lateral fissure

<img src="https://upload.wikimedia.org/wikipedia/commons/9/96/Brain_diagram_fr.png" width="800px" style="display: block; margin: auto;" />

- Primary auditory cortex
- Object, face recognition
- Storage of memories about events, objects 
- Amygdala, hippocampus

**Inferior Temporal Gyrus (ITG)**

<img src="https://upload.wikimedia.org/wikipedia/commons/1/18/Gray726_inferior_temporal_gyrus.png" width="800px" style="display: block; margin: auto;" />

**Entorhinal Cortex (ER)**

<img src="https://upload.wikimedia.org/wikipedia/commons/1/15/Medial_surface_of_cerebral_cortex_-_entorhinal_cortex.png" width="800px" style="display: block; margin: auto;" />

###### Parietal lobe

- Caudal to frontal lobe
- Dorsal to temporal lobe
- Posterior to central sulcus

<img src="https://upload.wikimedia.org/wikipedia/commons/9/96/Brain_diagram_fr.png" width="800px" style="display: block; margin: auto;" />

- Primary somatosensory cortex
- Perception of spatial relations, action planning

**Inferior Parietal Lobule**

<img src="https://upload.wikimedia.org/wikipedia/commons/e/e3/Gray726_inferior_parietal_lobule.png" width="800px" style="display: block; margin: auto;" />

**Superior Parietal Lobule**

<img src="https://upload.wikimedia.org/wikipedia/commons/9/9d/Gray726_superior_parietal_lobule.png" width="800px" style="display: block; margin: auto;" />

###### Occipital lobe

- Caudal to parietal & temporal lobes

<img src="https://upload.wikimedia.org/wikipedia/commons/9/96/Brain_diagram_fr.png" width="800px" style="display: block; margin: auto;" />

- Primary visual cortex (V1)

<img src="http://bethycotter.wdfiles.com/local--files/introducingtheeye/Screen%20Shot%202012-08-24%20at%2011.36.20%20PM.png" width="800px" style="display: block; margin: auto;" />

###### Insular cortex (insula)

- medial to temporal lobe
- deep inside lateral fissure

<img src="https://upload.wikimedia.org/wikipedia/commons/b/b4/Sobo_1909_633.png" width="800px" style="display: block; margin: auto;" />

- Primary gustatory cortex
- Self-awareness, interpersonal experiences, motor control, interoception

##### Brodmann Areas

- [Korbinian Brodmann](https://en.wikipedia.org/wiki/Korbinian_Brodmann)

<img src="http://www.spektrum.de/lexika/images/bio/fff1209_w.jpg" width="800px" style="display: block; margin: auto;" />

- Cytoarchitectonic (cellular architecture) differences in cerebral cortex
- Numbered areas

<img src="https://upload.wikimedia.org/wikipedia/commons/0/09/Brodmann-areas.png" width="800px" style="display: block; margin: auto;" />

<img src="http://www.brain-maps.com/gehirn/brodmann_areale.jpg" width="800px" style="display: block; margin: auto;" />

## White matter pathways

- Brainstem
- Projection fibers
- Association fibers
- Commissural fibers

<img src="img/brainstem-white-matter-schematic.jpg" width="800px" style="display: block; margin: auto;" />

[[@oishi2010mri]](https://books.google.com/books?hl=en&lr=&id=v8MWjTpVUAYC&oi=fnd&pg=PT1&dq=mri+atlas+of+human+white+matter&ots=mV146PeNPd&sig=2HjnDc0IxdCj-EVap1Gr77XIw7U#v=onepage&q=mri%20atlas%20of%20human%20white%20matter&f=false), Chapter 3, Figure 1.

### Brainstem projections

- Corticospinal tract (descending/efferent)
- Dorsal column/medial lemniscus (ascending/afferent)
- Superior/inferior cerebellar peduncles (from/to cerebellum)

<img src="img/projection-fiber-schematic.jpg" width="800px" style="display: block; margin: auto;" />

[[@oishi2010mri]](https://books.google.com/books?hl=en&lr=&id=v8MWjTpVUAYC&oi=fnd&pg=PT1&dq=mri+atlas+of+human+white+matter&ots=mV146PeNPd&sig=2HjnDc0IxdCj-EVap1Gr77XIw7U#v=onepage&q=mri%20atlas%20of%20human%20white%20matter&f=false), Chapter 3, Figure 8.

### Projection fiber tracts

- Internal capsule
    - Thalamic radiation
    - Cortico-{pontine, bulbar, reticular} tracts

<img src="img/cortical-white-matter-schematic.jpg" width="800px" style="display: block; margin: auto;" />

<img src="img/cortical-white-matter.jpg" width="800px" style="display: block; margin: auto;" />

[[@oishi2010mri]](https://books.google.com/books?hl=en&lr=&id=v8MWjTpVUAYC&oi=fnd&pg=PT1&dq=mri+atlas+of+human+white+matter&ots=mV146PeNPd&sig=2HjnDc0IxdCj-EVap1Gr77XIw7U#v=onepage&q=mri%20atlas%20of%20human%20white%20matter&f=false), Chapter 3, Figure 11.

### Cortical white matter tracts

- Superior/inferior longitudinal fasciculus
    - [Arcuate fasciculus](https://en.wikipedia.org/wiki/Arcuate_fasciculus) part of sup. long. f.
- Superior/inferior fronto-occipital fasciculus
- Cingulum, fornix (hyp-hip), stria terminalis (hyp-amyg)

### Commissural fibers

- Corpus callosum
- Anterior commissure (AC)
- Posterior commissure (PC)

<img src="https://upload.wikimedia.org/wikipedia/commons/6/60/Corpus_callosum.png" width="800px" style="display: block; margin: auto;" />

<img src="https://i.redd.it/7qobxge7gp611.jpg" width="800px" style="display: block; margin: auto;" />
<!-- Corpus Callosum -->

**Anterior, Posterior Commissures**

<img src="https://upload.wikimedia.org/wikipedia/commons/2/22/Gray720.png" width="800px" style="display: block; margin: auto;" />

## Spinal cord

- Spinal column w/ vertebrae
- Cervical (8), thoracic (12), lumbar (5), sacral (5), coccygeal (1)
- Spinal segments & 31 nerve pairs 
- Cauda equina

<img src="http://www.fauxpress.com/kimball/med/sensory/spinaldivisions.jpg" width="800px" style="display: block; margin: auto;" />

- Dorsal/Ventral
    + Dorsal root (sensory)
    + Ventral root (mostly motor)
- Grey (interior) vs. white matter (exterior)

<img src="https://image.slidesharecdn.com/thespinalcord-2003-141108070925-conversion-gate02/95/the-spinal-cord-4-638.jpg?cb=1415430697" width="800px" style="display: block; margin: auto;" />
<!-- Cross section of the spinal cord. -->

<img src="https://upload.wikimedia.org/wikipedia/commons/e/e6/Gray675.png" width="800px" style="display: block; margin: auto;" />

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/dc/Medulla_spinalis_-_Section_-_English.svg/1024px-Medulla_spinalis_-_Section_-_English.svg.png" width="800px" style="display: block; margin: auto;" />

# Organization of the PNS 

- Somatic division
- Autonomic division (Autonomic Nervous System)

## Somatic division

### Cranial nerves

- Afferents (input), efferents (output), or mixed
- Innervate head and neck
- Olfactory (I), optic (II), (VIII) auditory,
vagus (X), etc. 
- Spinal nerves

<img src="http://media-1.web.britannica.com/eb-media/44/54244-004-892C5169.jpg" width="800px" style="display: block; margin: auto;" />

### Spinal nerves

<img src="https://www.pastmedicalhistory.co.uk/wp-content/uploads/2018/08/A-model-of-the-human-nervous-system-by-Rufus-Benjamin-Weaver..jpg" width="800px" style="display: block; margin: auto;" />

## Autonomic nervous system

- CNS & PNS components
- Controls “vegetative functions”
    + Limited voluntary control
- Two divisions
    + Sympathetic
    + Parasympathetic

<img src="https://4.bp.blogspot.com/_FBNLGBBprSE/TB5b9zkM11I/AAAAAAAAAHA/LBCT2HkOzvI/s400/PNS.GIF" width="800px" style="display: block; margin: auto;" />

### Sympathetic division

- Prepares body for action
- “Fight or flight”
- Spinal cord
    + ganglion chain along spinal column to End organs
- Neurotransmitters (NTs)
    + Preganglionic: ACh 
    + Post: NE
    
### Parasympathetic division

- “Around” sympathetic
- Restorative function
- “Rest & digest”
- Spinal cord (or Vagus n.) -> ganglia near end organs -> end organ
    + NT: ACh

## References {.smaller}
