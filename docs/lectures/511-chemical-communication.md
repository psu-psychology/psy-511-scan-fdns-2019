---
title: "511-chemical-communication"
author: "Rick Gilmore"
date: "2019-09-26 17:33:19"
bibliography: bib/bibliography.bib
csl: bib/apa.csl
css: css/outline.css
output:
  html_document:
    keep_md: true
    theme: lumen
    toc: yes
    toc_depth: 5
    toc_float: no
    code_folding: hide
---



# Fun

<iframe width="420" height="315" src="https://www.youtube.com/embed/gsjcb7w1Y-w" frameborder="0" allowfullscreen></iframe>

# Neural communication

## What triggers the action potential?

- Soma receives input from dendrites (and on soma directly)
- Axon hillock sums/integrates
- If sum > threshold, action potential "fires"
- Action potential propagates along the axon

<div class="figure" style="text-align: center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a2/1224_Post_Synaptic_Potential_Summation.jpg/512px-1224_Post_Synaptic_Potential_Summation.jpg" alt="Source: https://commons.wikimedia.org/wiki/File%3A1224_Post_Synaptic_Potential_Summation.jpg" width="800px" />
<p class="caption">Source: https://commons.wikimedia.org/wiki/File%3A1224_Post_Synaptic_Potential_Summation.jpg</p>
</div>

- Action potential's rapid change in voltage triggers neurotransmitter (NT) release

## Synaptic transmission

*Synapse* permits neuron to pass electrical or chemical messages to another neuron or target cell (muscle, gland, etc.) 

### Synapse Types

- Electrical
  - Gap junctions
  - *Cytosol* (and ionic current) flows through adjacent neurons 
- Chemical

<div class="figure" style="text-align: center">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/33/Blausen_0843_SynapseTypes.png" alt="Source: Blausen.com staff https://commons.wikimedia.org/wiki/File%3ABlausen_0843_SynapseTypes.png" width="800px" />
<p class="caption">Source: Blausen.com staff https://commons.wikimedia.org/wiki/File%3ABlausen_0843_SynapseTypes.png</p>
</div>

### Steps in chemical transmission

- *Voltage-gated calcium Ca++ channels* open
- Ca++ influx causes *synaptic vesicles* to bind with presynaptic membrane, fuse with membrane, spill contents via *exocytosis*
- NTs diffuse across *synaptic cleft*
- NTs bind with *receptors* on *postsynaptic membrane*
  - Cause some post-synaptic effect
- NTs unbind from receptor
- NTs inactivated

<div class="figure" style="text-align: center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/30/SynapseSchematic_en.svg/512px-SynapseSchematic_en.svg.png" alt="Source: https://commons.wikimedia.org/wiki/File%3ASynapseSchematic_en.svg" width="800px" />
<p class="caption">Source: https://commons.wikimedia.org/wiki/File%3ASynapseSchematic_en.svg</p>
</div>

<img src="http://webvision.med.utah.edu/imageswv/GLU5.jpeg" width="800px" style="display: block; margin: auto;" />

### Exocytosis


<div class="figure" style="text-align: center">
<img src="http://www.nature.com/nrn/journal/v12/n3/images/nrn2948-f1.jpg" alt="Source: http://dx.doi.org/doi:10.1038/nrn2948" width="800px" />
<p class="caption">Source: http://dx.doi.org/doi:10.1038/nrn2948</p>
</div>

### Receptor/channel types

#### Leak/passive

- Vary in selectivity, permeability

#### Transporters/exchangers

+ Ionic
    * $Na^+$/$K^+$ ATP-ase/pump
+ Chemical
    * e.g., Dopamine transporter (DAT)

#### Ionotropic receptors (receptor + ion channel)

- Ligand-gated
- Open/close channel

#### Metabotropic receptors (receptor only)

- Triggers 2nd messengers
- G-proteins
- Open/close adjacent channels, change metabolism

<img src="https://classconnection.s3.amazonaws.com/94/flashcards/1500094/jpg/chemical_synapse1355159626230.jpg" width="800px" style="display: block; margin: auto;" />

### Receptors generate *postsynaptic potentials (PSPs)*

- Small voltage changes
- Amplitude scales with # of receptors activated
- *Excitatory PSPs (EPSPs)*
    + Depolarize neuron (make more +)
- *Inhibitory (IPSPs)*
    + Hyperpolarize neuron (make more -)

### NTs inactivated

- Buffering
    + e.g., glutamate into astrocytes
- Reuptake into presynaptic cell via transporters
    + e.g., serotonin via serotonin transporter (SERT)
- Enzymatic degradation
    + e.g., acetylcholine esterase (AChE) degrades acetylcholine (ACh)

### Questions to ponder

- Why do NTs diffuse from pre- to post-synaptic membrane?
- Why must NTs be inactivated?
- What sort of PSP would *opening* a Na+ channel produce?
- What sort of PSP would *opening* a Cl- channel produce?
- What sort of PSP would *closing* a K+ produce?

### Synapse location and function

- dendrites
    + usually excitatory 
- cell bodies
    + usually inhibitory 
- axons 
    + usually modulatory (change p(fire))

<img src="https://classconnection.s3.amazonaws.com/94/flashcards/1500094/jpg/chemical_synapse1355159626230.jpg" width="800px" style="display: block; margin: auto;" />

## Neurotransmiters

| Family      | Neurotansmitter                     |
|-------------|-------------------------------------|
| Amino acids | [Glutamate](https://en.wikipedia.org/wiki/Glutamate_(neurotransmitter))                           |
|             | [$\gamma$ aminobutyric acid (GABA)](https://en.wikipedia.org/wiki/Gamma-Aminobutyric_acid)      |
|             | Glycine                             |
|             | Aspartate                           |

### Glutamate

- Primary excitatory NT in CNS
- Role in learning (via NMDA)
- Receptors on neurons and glia (astrocytes and oligodendrocytes)
- Linked to umami (savory) taste sensation (think monosodium glutamate or MSG)
- Dysregulation in schizophrenia? [[@javitt2010glutamatergic]](http://search.proquest.com/openview/b3f476465105142b104ba03c9c9b490c/1?pq-origsite=gscholar)

| Type         | Receptor   | Esp Permeable to |
|--------------|------------|------------------|
| Ionotropic   | AMPA       | Na+, K+          |
|              | Kainate    |                  |
|              | NMDA       | Ca+              |
| Metabotropic | mGlu       |                  |

### $\gamma$ aminobutyric acid (GABA)

- Primary inhibitory NT in CNS
- Excitatory in developing CNS, [Cl-] in >> [Cl-] out
- Binding sites for benzodiazepines (e.g., Valium), barbiturates, ethanol, etc.

| Type         | Receptor   | Esp Permeable to |
|--------------|------------|------------------|
| Ionotropic   | GABA-A     | Cl-              |
| Metabotropic | GABA-B     | K+                 |

<div class="figure" style="text-align: center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/45/GABAA-receptor-protein-example.png/1200px-GABAA-receptor-protein-example.png" alt="Source: https://commons.wikimedia.org/wiki/File:GABAA-receptor-protein-example.png#/media/File:GABAA-receptor-protein-example.pn" width="800px" />
<p class="caption">Source: https://commons.wikimedia.org/wiki/File:GABAA-receptor-protein-example.png#/media/File:GABAA-receptor-protein-example.pn</p>
</div>

### Other amino acid NTs

- *Aspartate*
    + Like Glu, stimulates NMDA receptor
- *Glycine*
    + Spinal cord interneurons

### Acetylcholine (ACh)

- Primary excitatory NT of CNS output
- Somatic nervous system (motor neuron -> neuromuscular junction)
- Autonomic nervous system (ANS)
    + Sympathetic branch: preganglionic neuron
    + Parasympathetic branch: pre/postganglionic
    
<div class="figure" style="text-align: center">
<img src="http://myzone.hrvfitltd.netdna-cdn.com/wp-content/uploads/2014/09/Image-1.jpg" alt="Source: http://myzone.hrvfitltd.netdna-cdn.com/wp-content/uploads/2014/09/Image-1.jpg" width="800px" />
<p class="caption">Source: http://myzone.hrvfitltd.netdna-cdn.com/wp-content/uploads/2014/09/Image-1.jpg</p>
</div>

| Type         | Receptor           | Esp Permeable to | Blocked by       |
|--------------|--------------------|------------------|------------------|
| Ionotropic   | Nicotinic (nAChR)  | Na+, K+          | e.g., Curare     |
| Metabotropic | Muscarinic (mAChR) | K+               | e.g., Atropine   |

### Curare

<img src="https://www.nybg.org/blogs/science-talk/content/uploads/2015/01/Curare-1.jpeg" width="800px" style="display: block; margin: auto;" />

<img src="http://www.general-anaesthesia.com/images/indian-curare.jpg" width="800px" style="display: block; margin: auto;" />

### Atropine

- aka, nightshade or belladonna
- inhibits (acts as an antagonist for) muscarinic ACh receptor

<div class="figure" style="text-align: center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/74/Eye_treated_with_dilating_eye_drops.jpg/800px-Eye_treated_with_dilating_eye_drops.jpg" alt="Source: https://commons.wikimedia.org/wiki/File:Eye_treated_with_dilating_eye_drops.jpg" width="800px" />
<p class="caption">Source: https://commons.wikimedia.org/wiki/File:Eye_treated_with_dilating_eye_drops.jpg</p>
</div>

## Monoamine NTs

| Family      | Neurotansmitter                         |
|-------------|-----------------------------------------|
| Monoamines  | Dopamine (DA)                           |
|             | Norepinephrine (NE)/Noradrenaline (NAd) |
|             | Epinephrine (Epi)/Adrenaline (Ad)       |
|             | Serotonin (5-HT)                        |
|             | Melatonin                               |
|             | Histamine                               |

### Information processing

- Point-to-point
    + One sender, small number of recipients
    + Glu, GABA
- Broadcast
    + One sender, widespread recipients
    + DA, NE, 5-HT, melatonin, histamine
- Need to know
    + NT, where projecting, type of receptor to predict function

### Dopamine

- Released by
    + Substantia nigra -> striatum, *meso-striatal projection*
    + Ventral tegmental area (VTA) -> nucleus accumbens, ventral striatum, hippocampus, amygdala, cortex; *meso-limbo-cortical projection*

<div class="figure" style="text-align: center">
<img src="http://thebrain.mcgill.ca/flash/a/a_03/a_03_cl/a_03_cl_que/a_03_cl_que_1a.gif" alt="Source: http://thebrain.mcgill.ca/flash/a/a_03/a_03_cl/a_03_cl_que/a_03_cl_que_1a.gif" width="800px" />
<p class="caption">Source: http://thebrain.mcgill.ca/flash/a/a_03/a_03_cl/a_03_cl_que/a_03_cl_que_1a.gif</p>
</div>

Clinical relevance for

- Parkinson's Disease (mesostriatal)
    + DA agonists treat (agonists facilitate/increase transmission)
- ADHD (mesolimbocortical)
- Schizophrenia (mesolimbocortical)
    + DA antagonists treat
- Addiction (mesolimbocortical)

Inactivated via

- Dopamine transporter (DAT) and chemical breakdown

<http://www.scholarpedia.org/article/Dopamine_anatomy#Dopamine_receptors>

| Type         | Receptor             | Comments                      |
|--------------|----------------------|-------------------------------|
| Metabotropic | D1-like (D1 and D5)  | more prevalent                |
|              | D2-like (D2, D3, D4) | target of many antipsychotics |

### Norepinephrine

- Released by
    + *[locus coeruleus](http://www.scholarpedia.org/article/Locus_coeruleus)* in pons
    + postganglionic sympathetic neurons onto target tissues
- Role in arousal, mood, eating, sexual behavior
- Monoamine oxidase inhibitors (MAOIs)
    + inactivate monoamines in neurons, astrocytes
    + MAOIs increase NE, DA
    + Treatment for depression

<div class="figure" style="text-align: center">
<img src="https://www.dartmouth.edu/~rswenson/NeuroSci/figures/Figure_9_files/image002.jpg" alt="Source: https://www.dartmouth.edu/~rswenson/NeuroSci/figures/Figure_9_files/image002.jpg" width="800px" />
<p class="caption">Source: https://www.dartmouth.edu/~rswenson/NeuroSci/figures/Figure_9_files/image002.jpg</p>
</div>

| Type         | Receptor             | Comments                           |
|--------------|----------------------|------------------------------------|
| Metabotropic | $\alpha$ (1,2)         | antagonists treat anxiety, panic   |
|              | $\beta$ (1,2,3)        | 'beta blockers' in cardiac disease |

### Serotonin (5-HT)

- Released by *raphe nuclei* in brainstem
- Role in mood, sleep, eating, pain, nausea, cognition, memory
- Modulates release of other NTs
- Most of body's 5-HT regulates digestion

<div class="figure" style="text-align: center">
<img src="https://www.dartmouth.edu/~rswenson/NeuroSci/figures/Figure_9_files/image002.jpg" alt="Source: https://www.dartmouth.edu/~rswenson/NeuroSci/figures/Figure_9_files/image002.jpg" width="800px" />
<p class="caption">Source: https://www.dartmouth.edu/~rswenson/NeuroSci/figures/Figure_9_files/image002.jpg</p>
</div>

- Separate cortical, subcortical 5-HT projection pathways?

<div class="figure" style="text-align: center">
<img src="https://3c1703fe8d.site.internapcdn.net/newman/csz/news/800/2018/anewmapofthe.jpg" alt="[[@Ren2018-zl]](http://dx.doi.org/10.1016/j.cell.2018.07.043)" width="800px" />
<p class="caption">[[@Ren2018-zl]](http://dx.doi.org/10.1016/j.cell.2018.07.043)</p>
</div>


- Seven recpeptor families (5-HT 1-7) with 14 types
- All but one metabotropic

Clinically significant because

- Ecstasy (MDMA) disturbs serotonin
- So does LSD
- Fluoxetine (Prozac)
    + *Selective Serotonin Reuptake Inhibitor (SSRI)*
    + Treats depression, panic, eating disorders, others
- 5-HT3 receptor antagonists are anti-mimetics used in treating nausea

### Melatonin

- Released by pineal gland (pine cone-like appearance)

<div class="figure" style="text-align: center">
<img src="http://www.vivo.colostate.edu/hbooks/pathphys/endocrine/otherendo/pinealgland.jpg" alt="http://www.vivo.colostate.edu/hbooks/pathphys/endocrine/otherendo/pinealgland.jpg" width="800px" />
<p class="caption">http://www.vivo.colostate.edu/hbooks/pathphys/endocrine/otherendo/pinealgland.jpg</p>
</div>

### Histamine

- Released by hypothalamus, projects to whole brain
- $H_1$-$H_4$ Metabotropic receptors, one ionotropic type in thal/hypothal
- Role in arousal/sleep regulation
- In body, part of immune/inflammatory response

## Targets of psychotropic drugs

<div class="figure" style="text-align: center">
<img src="img/psychotropic-drug-targets.jpg" alt="Source: https://stahlonline.cambridge.org/essential_4th_chapter.jsf?page=chapter2_summary.htm&amp;name=Chapter%202&amp;title=Summary" width="800px" />
<p class="caption">Source: https://stahlonline.cambridge.org/essential_4th_chapter.jsf?page=chapter2_summary.htm&name=Chapter%202&title=Summary</p>
</div>

## Other NTs

- Gases
    + *Nitric Oxide (NO)*, *carbon monoxide (CO)*
- Neuropeptides
    + *Substance P* and *endorphins* (endogenous morphine-like compounds) have role in pain
    + *Orexin/hypocretin*, project from lateral hypothalamus across brain, regulates appetite, arousal
    + *Cholecystokinin (CCK)* stimulates digestion
- Purines
    + *Adenosine* (inhibited by caffeine)
- Others
    + *Anandamide* (activates endogenous cannabinoid receptors)



# Hormonal communication

- Chemicals secreted into blood
- Act on specific target tissues via receptors
- Produce specific effects

## Examples of substances that are both hormones and NTs
    
- Melatonin
- Epinephrine/adrenaline
- Oxytocin
- Vasopressin
    
## Behaviors under hormonal influence

### Ingestive (eating/ drinking)

+ ￼Fluid levels
+ Na, K, Ca levels 
+ Digestion
+ Blood glucose levels

### Reproduction-related

+ Sexual Maturation
+ Mating
+ Birth
+ Care giving

### To threat/challenge

+ Metabolism
+ Heart rate, blood pressure 
+ Digestion
+ Arousal

### Common factors

- Biological imperatives
- Proscribed in space and time
- Foraging/hunting
    + Find targets distributed in space, evaluate, act upon
- Often involve others

## Principles of hormonal action

- Gradual action
- Change intensity or probability of behavior 
- Behavior influences/influenced by hormones
    + +/- Feedback
- Multiple effects on different tissues
- Produced in small amounts; released in bursts 
- Levels vary daily, seasonally
    + or are triggered by specific external/internal events
- Effect cellular metabolism 
- Influence only cells with receptors
- Point to point vs.“broadcast”
    + Wider broadcast than neuromodulators
- Fast vs. slow-acting
- Short-acting vs. long-acting
- Digital (yes-no) vs. analog (graded) 
- Voluntary control vs. involuntary

### Similarities between neural and hormonal communication

- Chemical messengers stored for later release 
- Release follows stimulation
- Action depends on specific receptors
- 2nd messenger systems common

### Hormonal release sites

<img src="img/glands.jpg" width="800px" style="display: block; margin: auto;" />

- CNS
    + Hypothalamus
    + *Pituitary*
        * *Anterior*
        * *Posterior*
    + Pineal gland
- Rest of body
    + *Thyroid*
    +  *Adrenal (ad=adjacent, renal=kidney) gland*
        * *Adrenal cortex*
        * *Adrenal medulla*
    + *Gonads* (testes/ovaries)

## Two release systems from hypothalamus 

### Direct release

- Hypothalamus (paraventricular, supraoptic nucleus) to
- Posterior pituitary
    + *Oxytocin*
    + *Arginine Vasopressin (AVP, vasopressin)*
        
<div class="figure" style="text-align: center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/70/1807_The_Posterior_Pituitary_Complex.jpg/594px-1807_The_Posterior_Pituitary_Complex.jpg" alt="Source: https://upload.wikimedia.org/wikipedia/commons/thumb/7/70/1807_The_Posterior_Pituitary_Complex.jpg/594px-1807_The_Posterior_Pituitary_Complex.jpg" width="800px" />
<p class="caption">Source: https://upload.wikimedia.org/wikipedia/commons/thumb/7/70/1807_The_Posterior_Pituitary_Complex.jpg/594px-1807_The_Posterior_Pituitary_Complex.jpg</p>
</div>

### Indirect release

- Hypothalamus -> *releasing hormones* 
- Anterior pituitary -> *tropic hormones*
- End organs

<img src="img/indirect-release.jpg" width="800px" style="display: block; margin: auto;" />

## Case studies

### Responses to threat or challenge

- Neural response
    + *Sympathetic Adrenal Medulla (SAM) response*
    + Sympathetic NS activation of adrenal medulla, other organs
    + Releases NE and Epi
    
<div class="figure" style="text-align: center">
<img src="http://www.nature.com/nrn/journal/v10/n6/images/nrn2647-i1.jpg" alt="[[@ulrich-lai_neural_2009]](http://doi.org/10.1038/nrn2647)" width="800px" />
<p class="caption">[[@ulrich-lai_neural_2009]](http://doi.org/10.1038/nrn2647)</p>
</div>

- Endocrine response
    + *Hypothalamic Pituitary Adrenal (HPA) axis*
    + Adrenal hormones released
- Hypothalamus
    + *Corticotropin Releasing Hormone (CRH)*
- Anterior pituitary
    + *Adrenocorticotropic hormone (ACTH)*
- Adrenal cortex
    + *Glucocorticoids (e.g., cortisol)*
    + *Mineralocorticoids (e.g. aldosterone)*
    
<div class="figure" style="text-align: center">
<img src="http://www.nature.com/nrn/journal/v10/n6/images/nrn2647-i1.jpg" alt="[[@ulrich-lai_neural_2009]](http://doi.org/10.1038/nrn2647)" width="800px" />
<p class="caption">[[@ulrich-lai_neural_2009]](http://doi.org/10.1038/nrn2647)</p>
</div>

### ￼Adrenal hormones

- *Steroids*
    + Derived from cholesterol
- *Cortisol*
    + increases blood glucose, anti-inflammatory effects
    + negative consequences of prolonged exposure 
- *Aldosterone*
    + Regulates Na (and water)
    
## Reproductive behavior -- the milk letdown reflex

- Supraoptic & Paraventricular nucleus (PVN) of hypothalamus releases oxytocin 
    - Into bloodstream via posterior pituitary (endocrine)
    - Onto neurons in nucleus accumbens (neurocrine), amygdala, brainstem

<div class="figure" style="text-align: center">
<img src="http://physiologyplus.com/wp-content/uploads/2017/05/milk-ejection-reflex.png" alt="http://physiologyplus.com/wp-content/uploads/2017/05/milk-ejection-reflex.png" width="800px" />
<p class="caption">http://physiologyplus.com/wp-content/uploads/2017/05/milk-ejection-reflex.png</p>
</div>

Oxytocin's role...

- Sexual arousal
- Released in bursts during orgasm
- Stimulates uterine, vaginal contraction
- Links to social interaction, bonding  [[@Weisman2013158]](http://dx.doi.org/10.1016/j.biopsych.2013.05.026)
- Alters face processing in autism  [[@Domes2013164]](http://dx.doi.org/10.1016/j.biopsych.2013.02.007)
- May inhibit fear/anxiety-related behaviors by gating amygdala [[@viviani2011oxytocin]](http://doi.org/10.1126/science.1201043)

<div class="centered">
<a href="http://columbusfreepress.com/sites/default/files/keep-calm-and-release-oxytocin-2(1).png">
<img src="http://columbusfreepress.com/sites/default/files/keep-calm-and-release-oxytocin-2(1).png" height=500px>
</a>
</div>

## Circadian rhythms

### Melatonin

- Diurnal rhythm
- Night time peak, early morning low
- Secretion suppressed by "blue" light (< 460-480 nm)
- Rhythm irregular until ~3 mos post-natal [[@Ardura2003-tw]](http://dx.doi.org/68571)
- Peak weakens, broadens with age

<img src="http://thebrain.mcgill.ca/flash/a/a_11/a_11_cr/a_11_cr_hor/a_11_cr_hor_1a.jpg" width="800px" style="display: block; margin: auto;" />

- Suprachiasmatic nucleus (SCN) of the hypothalamus
- Paraventricular nucleus of the hypothalamus
- Spinal cord
- Superior cervical ganglion
- Pineal gland

<iframe width="560" height="315" src="https://www.youtube.com/embed/fgJPnQCJ9eE" frameborder="0" allowfullscreen></iframe>

## Thinking about neurochemical influences

- Measure hormones in blood, saliva; can't effectively measure NTs
- Multivariate, nonlinear, mutually interacting
- Varied time scales
    - Phasic (e.g., cortisol in response to challenge)
    - Periodic (e.g., melatonin; diurnal cortisol)
- Peripheral effects + neural feedback
- State variables and behavior
    - Are your participants sleepy, hungry, horny, distressed...
    - Endogenous & exogenous influences

### Gut/brain connection

<div class="figure" style="text-align: center">
<img src="https://ars.els-cdn.com/content/image/1-s2.0-S0166223616301138-gr1.jpg" alt="[[@Sarkar2016-qf]](https://doi.org/10.1016/j.tins.2016.09.002)" width="800px" />
<p class="caption">[[@Sarkar2016-qf]](https://doi.org/10.1016/j.tins.2016.09.002)</p>
</div>

# References
