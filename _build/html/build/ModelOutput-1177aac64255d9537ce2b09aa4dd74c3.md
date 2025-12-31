# Understanding model output
The *DiatomSizeESS* model outputs two tables of results, and two sets of plots, after each simulation run.

## Tabular results
Tabular results are shown in the noteboook cell under the **Run simulation** button, and also saved in the text files [](standingstocks.txt) and [](./losses.txt)[^over].
```{figure} ./Images/DESS_7.png
:label: out1
:alt: DiatomSizeESS tabular output
:align: center
:width: 500

Top: Table of standing stock statistics, averaged over the last mixing interval.
Bottom: Table of biovolume losses, averaged over the last mixing interval.
```
In these tables, the columns represent: $i$ - size class, $s$ - size, $10^s$ - cell volume, $N$ - number of cells, $Q/Q_{min}$ - fractional nutrient quota, $BV$ - biovolume, $M$ - "background" mortality, $S$ - sinking mortality, $L$ - mixing event mmortality

## Starting a population simulation
Running simulations with a new population using the model requires three steps:
1. Select parameters under **Setting up diatom variants and mixed layer characteristics**, then click **Set up population**
2. Select parameters under **Seeding the mixed layer with diatom variants**, and click **Seed cell population**
3. Select parameters under **Setting mixing event intervals, and running the simulation** and click **Run simulation**

## Continuing a population simulation
Continuing a simulation (without resetting the population) requires two steps:
1. [optionally] Add cells by selecting parameters under **Seeding the mixed layer with diatom variants**, and clicking **Seed cell population**
2. Select parameters under **Setting mixing event intervals, and running the simulation** and click **Run simulation**.

You can add cells, and/or continue the simulation, as many times as you want.






[^over]: Note that these files are over-written each time the simulation is run.








