---
title:  "Hurting from a boo-boo? Blame Mrgpr2!"
---

<h4>Our fun aside for this week is Cre-Lox recombination! And no, this has nothing to do with smoked salmon.</h4>

Suppose you'd like to target a cell population based on a protein it expresses (think Mrgpr2). Maybe you want to make those cells susceptible to a diptheria toxin so you can wipe them out of your mouse, or maybe you just want to fluorescently label them. The Cre-Lox handles this problem by specifically modifying the DNA of cells that have used a certain promoter to express a gene of interest.

When a mouse is bred to have a Cre-protein that is controlled under the same promoter as your gene of interest, Cre will be expressed whenever you gene of interest is expressed. What makes Cre special is that it chops out DNA between sequences of loxP sites. In the picture below, a mouse is bred to have Cre under the same promoter of a blue gene and a green gene. When some cell in thise mouse begins to try expressing the blue gene, Cre will get expressed and cut out the blue gene from that cell's genome, as it lies between two loxP sites. This cell and all of its descendants will never be able to produce the blue gene again. It is important that this process is localized to cells that express this blue gene, meaning Cre will not act unless a cell has tried to express the blue gene.

<figure>
  <img src="/assets/images/post_images/CreLoxP_experiment.png" style="width:100%">
  <figcaption>Image by Matthias Zepper.</figcaption>
</figure>

The other important piece of this system is the green gene that now gets expressed after the blue has been excised. This gene can simply encode a fluorescent protein that will glow a specific color to allow you to visualize where cells that tried expressing your blue gene are located. If you want to use Cre-Lox to wipe out these cells instead, you can make this green gene a protein, not seen on any other cell, that binds a specific toxin. Cells that have tried expressing the blue gene will then become the only cells in the mouse sensitive to this toxin, and can be wiped out by administering the toxin to the mouse. 
