## Possible Questions

The purpose of this assignment is to (a) familiarize you with an important result from computational neuroscience (b) give you an appreciation for the various levels of detail you can use when modeling neural systems. The Hodgkin-Huxley model is very successful at modeling action potentials, however it is computationally costly and requires many parameters. Some neuroscience research programs such as the Blue Brain Project choose to model neural systems at this level of granularity (in fact they go even further and build multi-compartment models of neurons). However, we think this is a mug's game and is not necessary for the modeling of biological neural networks. Hopefully by the end of this exercise, you will agree.

1. Hodgkin and Huxley recieved the Nobel Prize in Physiology or Medicine in 1963 for their work on ionic mechanisms underlying the initiation and propagation of action potentials (in the squid giant axon). This work was articulated in a series of papers from 1952, the last of which was titled _A Quantitaive Description of Membrane Current and its Application to Conduction and Excitation in Nerve_. This seminal paper is somewhat difficult to read, but given some background, it should be possible to parse through the important points.
    1. As background, read/skim Chapter 5 of [Theoretical Neuroscience](https://ebookcentral.proquest.com/lib/columbia/detail.action?docID=3338869) (accessible via [CLIO](https://clio.columbia.edu/catalog/13025930?counter=1)) with a focus on sections 5.5 "Voltage Dependent Conductances" and 5.6 "The Hodgkin-Huxley Model." In your summary, be sure to address the following:
        1. What is a neuronal membrane potential, and what determines its value?
        2. What is the resting potential? What is the reversal potential?
        3. What are voltage-dependent conductances?
    
    2. Read/skim the original paper [A Quantitaive Description of Membrane Current and its Application to Conduction and Excitation in Nerve](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1392413/pdf/jphysiol01442-0106.pdf) and summarize in your own words how they arrived at their set of 4 coupled equations:
    
    ![equation](https://latex.codecogs.com/png.latex?I&space;=&space;C_m\frac{{\mathrm&space;d}&space;V_m}{{\mathrm&space;d}&space;t}&space;&plus;&space;\bar{g}_\text{K}n^4(V_m&space;-&space;V_K)&space;&plus;&space;\bar{g}_\text{Na}m^3h(V_m&space;-&space;V_{Na})&space;&plus;&space;\bar{g}_l(V_m&space;-&space;V_l))
    
    ![equation](https://latex.codecogs.com/png.latex?\frac{dn}{dt}&space;=&space;\alpha_n(V_m)(1&space;-&space;n)&space;-&space;\beta_n(V_m)&space;n)
    
    ![equation]()
    
    ![equation]()
    
    Be sure to articulate what assumptions they made in their modeling

![equation](https://latex.codecogs.com/png.latex?I&space;=&space;C_M&space;\frac{dV}{dt}&space;&plus;&space;I_i)
