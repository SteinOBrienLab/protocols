---
title: Cephalopod Embryo Dissociation - Optimized protocol

subtitle: Gentle dissociation and fixation of cephalopod embryos for sci-RNA-seq3 input
date: Jun 7, 2024
Author: Caroline Albertin
Author: Loyal A. Goff
bibliography: [references.bib]
---

<link href="styles.css" rel="stylesheet">
<span class="note">Updated:</span> Jun 16, 2024

## Table of Contents
- [Table of Contents](#table-of-contents)
- [Setup](#setup)
  - [Reagents](#reagents)
  - [Materials](#materials)
  - [Buffers](#buffers)
    - [Ca-Mg2 Free Artificial Seawater (ASW)](#ca-mg2-free-artificial-seawater-asw)
    - [Ca-Mg2 Free Artificial Seawater (ASW) + 4% BSA](#ca-mg2-free-artificial-seawater-asw--4-bsa)
    - [Salt-Adjusted TryplE Express](#salt-adjusted-tryple-express)
- [Mechanical Dissociation](#mechanical-dissociation)
  - [Questions:](#questions)
  - [Preparation of single cell suspension](#preparation-of-single-cell-suspension)
  - [Fixation with Methanol + DSP (Lomant's Reagent)](#fixation-with-methanol--dsp-lomants-reagent)

## Setup

### Reagents

### Materials
- 1.5 ml Microcentrifuge tubes (clear)
- P1000 pipette tips
- Dounce homogenizer (1mL; 'loose' pestle)
- Centrifuge
- Rocker
- Cell strainer, 70 μm mesh (e.g. FALCON #352350)
- Cell strainer, 40 μm mesh (e.g. FALCON #352340)
- 50 ml Conical tubes
- Hemocytometer or automated cell counter
- Trypan blue or other cell viability dye

### Buffers

#### Ca-Mg2 Free Artificial Seawater (ASW)

|Reagent	| Quantity (for 500 mL)	| Final concentration
|------------|---------------------|---------------------|
|NaCl      | 13.1g    | 450 mM |
|KCl      | 0.335g    | 9 mM | 
|Na<sub>2</sub>SO<sub>4</sub> | 2.31g    | 30 mM |
|NaHCO<sub>3</sub> | 0.105g    | 2.5 mM |
|Tris-HCl  | 5mL 1M (pH 8.0) | 10 mM |
|EDTA      | 2.5mL of 0.5M (pH 8.0) | 2.5 mM |
|HEPES     | 12.5mL of 1M (pH 6.9) | 25 mM |
| Nuc Free Water to 500mL (pH 6.9-7.4)   ||

- Filter sterilize and store at 4°C

#### Ca-Mg2 Free Artificial Seawater (ASW) + 4% BSA
|Reagent	| Quantity (for 50 mL)	| Final concentration
|------------|---------------------|---------------------|
|Ca-Mg2 Free ASW | 50mL | - |
|BSA | 2g | 4% |

#### Salt-Adjusted TryplE Express
|Reagent	| Quantity (for 50 mL)	| Final concentration
|------------|---------------------|---------------------|
|TryplE Express | 14mL | - |
|5M NaCl | 1mL  | 333mM |


## Mechanical Dissociation
1. Collect embryos or larvae at the desired stage.
2. Dechorionate embryos in Filtered Natural Sea Water or ASW.
3. Transfer embryos or larvae into 1.5 ml microcentrifuge tube   
  - ∼ 20 embryos/tube $\lt$St26 Dpe embryos 
  - ∼ 10 embryos/tube $\ge$St26 Dpe embryos
4. Pulse spin to collect as needed.
5. Wash embryos in 1mL ice cold[Calcium and Magnesium free ASW](#ca-mg2-free-artificial-seawater-asw) (x2)
     - <span class="critical">CRITICAL:</span> Do not freeze samples unless you are making nuclei. Freezing will destroy the cell membrane and make viable dissociation impossible.
6. Resuspend in  1mL [Salt-supplemented TryplE](#salt-adjusted-tryple-express). Gently triturate.(#ca-mg2-free-artificial-seawater-asw). 
7. Transfer to 1mL glass dounce homogenizer and gently grind embryos $\le$10 strokes with the _loose_ pestle.
8. Transfer back to new 1.5 mL tube and gently triturate with P1000 pipette tip.
9. Place on rocker for 5-10 minutes at room temperature.
    - Gently triturate with P1000 pipette tip every 5 min.
    - 5 min for earlier embryos, 10 min for later stage embryos.
10. Filter cells through 70uM filter into a 50mL concial
11. Transfer cells to 15 mL conical for spin down
    - Creates a better pellet.
12. Wash with 2mL [Ca-Mg free ASW with 4% BSA](#ca-mg2-free-artificial-seawater-asw--4-bsa). 
13. Spin cells gently at 1000 rpm (~161xg) (or lowest setting that pellets cells) for 3' at 4ºC
14. Decant supernatant
15. Gently resuspend cells in 3mL [Ca-Mg free ASW with 4% BSA](#ca-mg2-free-artificial-seawater-asw--4-bsa) by pipetting up and down to disaggregate pellet.
16. Filter cells through 40uM filter into a 50mL conical.
17. Transfer to 15 mL conical for spin down.
18. Spin cells gently at 1000 rpm (161xg) for 3' at 4ºC
19. Decant supernatant
20. Gently resuspend cells in **1mL** [Ca-Mg free ASW with 4% BSA](#ca-mg2-free-artificial-seawater-asw) by pipetting up and down to disaggregate pellet.
21. Check cell viability and concentration on hemocytometer by combining 10uL cells with 10uL trypan blue, load 10uL onto hemocytometer. 
    - If there is a lot of debris, repeat BSA washes.
    - <span class="note">Note:</span> Especially for earlier stages, you may see a number of large, Trypan blue<sup>+</sup> lipid droplets.  These are from the yolk and they naturally stain blue. Do not count these as cells (live or dead) in your hemocytometer count.
    - <span class="todo">TODO:</span> Still need to confirm that lipid droplets will not affect library prep downstream.
22. Proceed to fixation step or store cells at 4ºC for up to 24 hours.

### <span class="todo">Questions:</span> 
  - should final resuspension have BSA and or FBS? (Is FBS even appropriate for marine cells?)
    - Does BSA need to be at 4%?  Is 1% enough to prevent clumping?
  - Can we supplement with Trehalose?
  - RNase inhibitor?

### Preparation of single cell suspension

CRITICAL: Keep the cell suspension at room temperature and do not store on ice.

### Fixation with Methanol + DSP (Lomant's Reagent)
