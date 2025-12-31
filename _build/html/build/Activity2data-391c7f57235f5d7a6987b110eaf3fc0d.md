# Activity 2: Data collection
The following steps take you through Activity 1.

## 1. Winners of competition in diverse diatom cultures
In a spreadsheet, start a table in which to record the winners of competitions in mixed layers with different mixing intervals:

```{figure} ./Images/Act2_1.png
:label: tab1
:alt: Table for recording standing stocks and nutrient concentrations for diatom monocultures.
:align: center
:width: 400

Table for recording dominant variants for different mixing intervals.
```
Data are collected in a nested loop:
```{figure} ./Images/Act2_2.png
:label: tab3
:alt: Schematic of data collection for Part 1
:align: center
:width: 400
Schematic of data collection for Part 1
```
- For each mixing interval, $T_{mix} = 1.5, 8, 18, 32$:
  - Execute the simulation sequence:  
	*Start a population $\rightarrow$ seed "all" size classes $\rightarrow$ run the simulation $\rightarrow$ record the winner*
Important:
- Make sure to run the simulation enough times to arrive at the true dominant variant &ndash; this can take **multiple runs**.
- **Record the winner** by entering its size class under "i_win" and its size under "s_win".
- Make sure to **record the approximate number of days** the model took for a dominant strain to emerge.

## Part 2: Do "winners" of competitions also form ESS's?
Do a new series of runs, to fill out the table column labeled "ESS".

Data are collected in a nested loop:
- For each mixing interval, $T_{mix} = 1.5, 8, 18, 32$:
  - Execute the simulation sequence, in two phases:  
	1. *Start a population $\rightarrow$ seed the dominant size class, $I_{win}$ $\rightarrow$ run the simulation*
	2. *Seed "all" size classes $\rightarrow$ run the simulation $\rightarrow$ assess if any variants grow*
- Record whether any variants are growing (that is, they have more cells than you seeded)

```{figure} ./Images/Act1_4.png
:label: tab4
:alt: Schematic of data collection for Part 2
:align: center
:width: 400
Schematic of data collection for Part 2
```
In the first phase, the candidate ESS variant establishes the nutrient environment.
In the second phase, other variants are tested to see whether they can grow in this nutrient environment.
