---
title: "Structure Function Papers"
date: 2023-03-19
description: "Annotating structure function papers"

---
This isn't much of a blog post but rather a starting point for myself to reference (on the fly, from anywhere) papers that I'm actively reading or have marked to read next. I hope others that find this post will be able to more quickly narrow down there search for a specific topic by using some of the annotations I've done.

As I can consider reading and diving deeper into the literature as my current [march 2023] priority, that will be reflected in this style of notes. I.e. I will be making an attempt to tabulate referenced papers. In papers that require mathematics (appences, toy problems, etc), I will switch, but for papers that are mostly word dense I will omit much as the best source is the primary linked one. I will also try to code out aspects of papers if it is ever meaningful and makes sense to do so.

**Note:**
* this is a living post that will be updated with future annotations
* any [0-9] refers to the citations listed within a given paper and you need to look in the paper to find out more about said reference

## Table of Contents
---
[[toc]]

## from the connectome to brain function
---
[`Cornelia I Bargmann & Eve Marder`]("https://d1wqtxts1xzle7.cloudfront.net/48812919/From_the_connectome_to_brain_function20160913-29300-1fosjpb-libre.pdf?1473811373=&response-content-disposition=inline%3B+filename%3DFrom_the_connectome_to_brain_function.pdf&Expires=1679198836&Signature=CZEwAYZT2Kg7O4qeLuD-jpVrn3uYoWzaDw6FrBpZm1E6CBXAu4MfMCHjMV4pbpnkBZzIAEVTBsvol52ApIQALKdMMLJr2WLTcdsW3jR7wxb2LTDyCVnOV7sK6YEF2o5fRON5amNmzsUqo4-RHdIoe4S6I-IHxkviuxC5SrNAps5g-zkQXvNFn4hmpT-yeNR5G8kTbciiDhaLAhkbj1LfkK7kdXDcUcNg~ZI~wJNGpomL4LBJ5OKI~dwIwxbzXB-1N9A73ZKlyl1LiC2ozNPQGGwZbt5Z2PGouhVgkpqjK3cU33sT~e9WnMiaXA59b2xIyryIXphvWS-LLoyfK53AXw__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA") @ 2013
<!-- here you would have a progress bar of hours spent on this post and how much you have spent so -->
<!-- far on it. time: 1:10:00 hr:min:sec -->

In this post, I'm going to read through a [`first pass`](https://web.stanford.edu/class/ee384m/Handouts/HowtoReadPaper.pdf)
of the aforementioned paper. This is in an effort to get as many [`hours`](https://www.youtube.com/watch?v=cdiD-9MMpb0) in as possible prior to diving into my independent summer research. 

<<<<<<< HEAD
### abstract
*Purpose:* 
What additional info is needed beyond connectivity diagrams to understand circuit function, informed by invertebrate circuits whose connectivity is known (in this case the C. elegans' nervous system is used as the anatomical connectome was established over 25 years ago i.e. 1980 [14])

*Key References:*
[5-7] identified nueronal components of circuits that generate behaviors by using systematic electrophysiological recording (19602, 1970s)
[14] "heroic electron microscopy reconstruction of the full nervous system of C. elegans" (1980's)
[4,15-18] "Recent advances in electron microscopy and image analysis have made it possible to scale up this ultrastructural approach: to serially section and reconstruct pieces of both vertebrate and invertebrate nervous systems, with the stated purpose of using detailed connectomes to reveal how these circuits work"

### What do functional and anatomical maps reveal?
Summary: Connectivity is complicated [^complicated]

Key takeaways:
* 60% of C. elegans neuron types have defined functions in one or more behaviors
* For C. elegans, although we know what most of the neurons do, we do not know what most of the connections do, we do not know which chemical connections are excitatory or inhibitory, and we cannot easily predict which connections will be important from the wiring diagram
* The wiring diagram could generate hypotheses to test, but solving a circuit by anatomical inspection alone was not successful. We believe that anatomical inspection fails because each wiring diagram encodes many possible circuit outcomes

Key References
[21] "The complexity of this connection map poses the essential question: are all synapses important, or are some only important under certain conditions (as appears to be the case)"

Reader notes:
* if you are skimming this I highly recommend taking a look at figures (1a) and (1b) to get a better idea of the difference between a connectivity diagram (1a) and a connectome (1b)
* connectome is organized in a signal flow view which reflects dominant information flow, from sensory neurons (top) -> interneurons (middle) -> motor neurons (bottom)

Additional connections are created by the widespread electrical synapses, mediated by direct cytoplasmic communication through gap junctions, through which current flows depending on the voltages of the coupled neurons. In the STG circuit, there are many instances of neurons that are connected by electrical synapses as well as by chemical inhibitory synapses[^complicated]



<!-- projects to build with code:
* sample heuristic of json activity ("firing") that has degenerate response clf ("actions") -->

## Reading List
* [A Modeling Framework for Deriving the Structure and Functional Architecture of a Short-Term Memory Microcircuit](https://drive.google.com/file/d/12peP0cvA6yXOCmo3HW1bdRqmGVuAAtg1/view?usp=share_link)
* [The space of interactions in neural network models](https://drive.google.com/file/d/1Fidly7Opqvq_lmegd3AD-AIYnxegTHgY/view?usp=share_link)
* [From connectome to brain function](https://drive.google.com/file/d/1lPd1AgE5EdPJYL5xKQulVKEEWymx5sGP/view?usp=share_link)
* [Geometrical and Statistical Properties of Systems of Linear Inequalities with Applications in Pattern Recognition](https://drive.google.com/file/d/1adQffIG-KziNR5JoiTB8QV7xNXzdKd_T/view?usp=share_link)
* [Sparse Coding with an Overcomplete Basis Set: A Strategy Employed by V1?](https://drive.google.com/file/d/1qFIHzCDTyFi6WiZCgGliVb10LMOix_Ep/view?usp=share_link)
* [Structural Properties of the Caenorhabditis elegans Neuronal Network](https://drive.google.com/file/d/1ETIxlWeSBeCc08WlUrZc8lISLPUWYsfC/view?usp=share_link)
=======
DRAFT:
* go through each major header, summarize key things that are worth mentioning, link any studies if it adds value
<!-- insert image of functional vs anatomical maps (how? lol)-->
Recency: Published 2013

Sub headers
* Abstract
* what do functional and anatomical maps reveal?
* parallel and antagonistic pathways complicate circuits
* Neuromodulation reconfigures circuit properties
* Neuronal dynamics shape the activity of circuits
* Vertebrate retina also has complex circuit properties
* Circuits interact to generate behavior
* How can we ‘solve’ the brain?
    is this identifiable now (a decade later)?
	" 
	Big science works best
	when the goals of a project are well-defined and when the out-
	comes can be easily recognized. Both were true about the human
	genome project, but neither is true, yet, about large-scale attempts
	to understand the brain.
	"

Summary of what complicates understanding neuron information flow and circuit-level dynamics:
* synaptic plasticity can occur on rapid timescales to strengthen and weaken synapses based on use, adding complexity to circuit-level dynamics

test:

![cbb088515b8f35cae64989b0ae7241da.jpg](:/5b9344861c1b4d39a7cb91db1212df39)


Citation:
Bargmann, C., Marder, E. From the connectome to brain function. Nat Methods 10, 483–490 (2013). https://doi.org/10.1038/nmeth.2451
>>>>>>> ed3b47224ca0ae8308ee22fa40a0892b2dd2050b

## Citations
* Bargmann, C., Marder, E. From the connectome to brain function. Nat Methods 10, 483–490 (2013). https://doi.org/10.1038/nmeth.2451


