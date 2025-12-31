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

## Graphical results
Two sets of graphical results are presented, each of which shows: (top) fractional quotas ($Q/Q_{min}$; (middle) biovolume ($BV$); and (bottom) mixed layer nutrient concentration ($R$).
1. *Period-averaged results, for all mixing intervals in the simulation.*  
  These plots show the long-term trends of diatom populations and nutrient.
  "Period-averaged" means the variation between mixing events is averaged out, so that the long-term trends are easier to see.
2. *Results during the last mixing interval.*  
  Variations during the last mixing interval.
  These plots show the transient response to a mixing event, which removes a fraction of the population but also adds nutrient to support new growth.

```{figure} ./Images/both.png
:label: out2
:alt: DiatomSizeESS period-averaged standing stock graphical output
:align: center
:width: 600

Left: Period-averaged results, over the simulation run.
Right: Plots  over the last mixing interval.
```

[^over]: Note that these files are over-written each time the simulation is run.








