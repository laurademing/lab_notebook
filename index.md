## Immortal Yeast Timeline

1/31 - diligence memo [posted](https://github.com/laurademing/lab_notebook/blob/main/investment_memo_technical)

Immortal Yeast - Technical Diligence

To make an immortal yeast, you could try to evolve a long-lived yeast, exploit a known biological pathway, or engineer the removal of known damage in yeast.

Because it seems like we don’t know all the damage types that kill yeast, and we aren’t sure how to prioritize the ones we do know about, evolving a longer-lived yeast strain might be the best first approach. Is that experiment doable?

STRATEGY 1: EVOLVE

Evolve a longer-lived yeast strain.

Unknowns: 
How would you design this experiment?
(MM had idea for selecting chronologically, then weeding out slow-growing daughters every cycle)
Are there other good ways to do this?
If the experiment design involves microfluidics, what is the cost and difficulty in setting this up?
Potential fast and cheap device to set up to get a feel for the system - https://www.sciencedirect.com/science/article/pii/S2468501119300069
In one example, a lab has trouble making more wafers, even though they have the original design (not clear what the takeaway should be).
https://www.nature.com/articles/nmeth.4609
How many cycles of directed evolution would we guess this would require, how long would that experiment take, and how much would the sequencing cost?
Yeast genome is ~12M bp, mutation rate is (10^-10), ~10^9 yeast per 1 ml of culture
Lifespan experiment with microfluidics might be 2-5 days per cycle (advantage over manual lifespans, where it would be ~weeks)
This still means a ~20x slowdown compared to something which can be selected for in each replication
Sequencing cost of a yeast genome is (?), for human is approaching ~$1K / genome and that is ~300x the size of a yeast genome, so presumably you could get it down to ~$100s?

STRATEGY 2: FAKE SPORULATION

Induce a sporulation-like regeneration process in an old cell periodically, to extend lifespan indefinitely.

Unknowns: 
What is the best next step for this experiment?
Why did expressing Ndt80 in a young yeast not lead to a similar lifespan extension to expressing it in an old yeast?
If you pulse expression of Ndt80 in old yeast, what is the effect?
What would the lead author of this paper suggest as the next step?
Are there other explanations for the experimental results observed?
If sporulation efficiency decreases with age (~3x, I think), could this experiment be selecting for the healthiest cells?
Should we expect non-Ndt80 proteins to also be required for full regeneration?

STRATEGY 3: ENGINEER (this is more of a backup strategy)

Try to specifically reverse the accumulation of different types of damage in yeast

Unknowns:
What damage, by how much to reverse
Next steps would be to quantify damage list made previously + thought experiments on yeast mental model to see what other kinds of damage might be appropriate 

EVALUATE

Define success criteria for the experiment. What is the gold standard that the winning yeast will have to meet?

Unknowns:
This is actually more subtle than it seems, and affects the choice of parameters for the strategies above.
What metric for health do we want to use?
The ability to replicate continuously >1000+ times, without visibly decreasing health?
The continuous ability to maintain metabolic health (as measured by protein turnover, or something else), for months or a year?
Are there any strategies for living longer that we won’t accept?
If sporulation does not count as immortality, what aspects of sporulation are we trying to avoid?
Does using replication to get rid of damage lead to any strains we would not accept?
Is there a metric for something very yeast specific that we would not accept?


TODO
Talk to someone who has done large and successful yeast experiments in directed evolution
Email lead author of sporulation regeneration paper
Talk to someone who has used microfluidics for yeast lifespan studies, and also someone who has a strong first-principles understanding of microfluidics
