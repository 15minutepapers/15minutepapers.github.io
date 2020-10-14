---
title:  "Hurting from a boo-boo? Blame Mrgpr2!"
excerpt: "Postdoc Dustin Green joins us to discuss the role of a mast cell receptor in pain"
sidebar:
  - keyterms:
      - term: "Mast Cell"
        defn: "Innate immune cells that are typically talked about in terms of allergies. They respond to foreign substances from the environment and signal other immune cells to enact an immune response (and in this case, also a nervous system response). "
      
      - term: "Mas-related G protein coupled receptors (Mrgprs)"
        defn: "G protein coupled receptors (GPCRs) are a class of receptors on cell surfaces that, when stimulated with their ligand, activate a signalling pathway inside the cell. Mrgprs are a family of GPCRs that are found on peripheral sensory neurons and mast cells. In this paper, the Mrgb2 receptor is responsible for activating mast cells to release cytokines."
      
      - term: "Peripheral sensory neuron"
        defn: "All the neurons in our body that aren’t in the spinal cord or brain that sense outside stimuli rather than doing what the brain tells them to. Those would be peripheral motor neurons."

      - term: "Mechanical and thermal hyperalgesia" 
        defn: "Atypical increased sensitivity to pain (mechanical → poking stimulus; thermal → heat stimulus). This is caused by neurogenic inflammation."

      - term: "Neurogenic inflammation" 
        defn: "The release of cytokines and recruitment of immune cells initiated by neurons."
      
      - term: "Substance P (SP)" 
        defn: "A peptide that binds to receptors on immune cells to regulate their inflammatory response. In the context of this paper, it’s the peptide released by neurons that binds the Mrgb2 receptor on mast cells to start the inflammation."
      - term: "Cytokines/chemokines" 
        defn: "Chemical messengers that signal for other cells to be activated and/or to migrate towards the damaged tissue. Some key examples from this paper were CCL2 and CCL3."

      - term: "NK-1R" 
        defn: "We didn’t talk about it much, but this was the most studied receptor that SP binds to; it was incorrectly thought to be the receptor that initiates the pain response. A lot of the reviewers of the paper were interested in the fact that SP wasn’t actually binding to this receptor during the pain response."





---

<h4>Our fun aside for this week is Cre-Lox recombination! And no, this has nothing to do with smoked salmon.</h4>

Suppose you’d like to target a cell population based on a protein it expresses (think Mrgpr2). Maybe you want to make those cells susceptible to a toxin so you can wipe them out of your mouse. Maybe you just want to fluorescently label them. The Cre-Lox system handles this problem by exploiting the same promoter as your gene of interest.
When a mouse is bred to have a Cre-protein that is controlled by the same promoter as your gene of interest, Cre will be expressed whenever your gene of interest is expressed. What makes Cre special is that it chops out DNA between sequences of loxP sites. This DNA will only be cut out if there are two loxP sites flanking the region (the fancy scientists call this a “floxed” gene). Usually you order mice with the region you want cut out already floxed, but if you hate yourself you can genetically engineer this on your own.

In the picture below, a mouse is bred to have Cre under the same promoter of a floxed gene (blue) and a reporter gene (green). When some cell in this mouse tries expressing the floxed gene, Cre will be expressed and cut this gene out. This cell and all of its descendants will never be able to produce the floxed protein again. It is important that this process is localized only to cells that have tried expressing the floxed gene.


<figure>
  <img src="/assets/images/post_images/CreLoxP_experiment.png" style="width:100%">
  <figcaption>Image by Matthias Zepper.</figcaption>
</figure>

After the floxed gene (blue) has been excised, your reporter gene (green) is now expressed. This gene could encode a fluorescent protein that allows you to visualize cells in which the floxed gene was removed. Or, the reporter protein could bind a toxin that selectively kills cells of interest. Once you inject the toxin into your mouse, any cell that had its floxed gene removed  will be wiped out, and the rest will be unharmed.

