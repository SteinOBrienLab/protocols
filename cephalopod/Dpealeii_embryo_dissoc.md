---
title: Doryteuthis pealeii Embryo Dissociation
subtitle: Gentle enzymatic dissociation and fixation of Doryteuthis pealeii embryos for input to sci-RNA-seq
date: Jun 3, 2024
Author: Loyal A. Goff
bibliography: [references.bib]
---

<link href="styles.css" rel="stylesheet">

## Table of Contents
- [Table of Contents](#table-of-contents)
- [Setup](#setup)
  - [Reagents](#reagents)
  - [Materials](#materials)
  - [Buffers](#buffers)
    - [Artificial seawater (ASW) - CSHL Protocols](#artificial-seawater-asw---cshl-protocols)
    - [ASW from dry salts](#asw-from-dry-salts)
    - [Dissociation Mix](#dissociation-mix)
      - [(for embryos 2–4 dpf)](#for-embryos-24dpf)
      - [(for embryos 5–16 dpf)](#for-embryos-516dpf)
  - [Reagent Prep](#reagent-prep)
- [Protocol](#protocol)
  - [Speciment Prep](#speciment-prep)
  - [Enzymatic Dissociation](#enzymatic-dissociation)
  - [Preparation of single cell suspension](#preparation-of-single-cell-suspension)

## Setup

### Reagents
- Collagenase from Clostridium histolyticum (Sigma #C9891)- 
- PBS 1X without Calcium and Magnesium (e.g. Corning #21-040-CV)
  - <span class="todo">TODO:</span> Replace with ASW or equivalent?
- DMEM 1X with 4.5 g/L glucose, L-glutamine & sodium pyruvate (Corning 10-013-CV)
  - <span class="todo">TODO:</span> Replace with ASW or equivalent?
- Fetal Bovine Serum (Fisher Scientific #SH30071.03HI) (to stop trypsin)
- 0.25% trypsin-EDTA (Gibco #25200-056)
  - <span class="todo">TODO:</span> Replace with TryplE or equivalent?
- Pharmaceutical grade buffered Tricaine methane sulfonate (MS-222)
  - <span class="todo">TODO:</span>This is likely EtOH instead for cephs.

### Materials
- Heat block set at 30 °C
- 1.5 ml Microcentrifuge tubes (clear)
- P1000 and P200 pipette tips
- Centrifuge
- Cell strainer, 70 μm mesh (e.g. FALCON #352350)
- 50 ml Conical tubes

### Buffers

#### Artificial seawater (ASW) - CSHL Protocols

|Reagent	| Quantity (for 1 L)	| Final concentration
|------------|---------------------|---------------------|
|NaCl	| 26.29 g	| 450 mM
|KCl	| 0.74 g	| 10 mM
|CaCl<sub>2</sub>	| 0.99 g	| 9 mM
|MgCl<sub>2</sub>·6H2O	| 6.09 g	| 30 mM
|MgSO<sub>4</sub>·7H2O	| 3.94 g	| 16 mM
| DI Water to 1L    |

  + pH 7.4
  + Filter sterilize and store at 4°C

#### ASW from dry salts

| Ingredient | Stock Concentration | Amt (g/L) | Molar Mass (g/mol) | Final Concentration (mM) |
|------------|---------------------|-----------|--------------------|---------------------------|
| NaCl       | -                   | 21.53     | 58.44              | 368                       |
| MgCl<sub>2</sub> | -             | 5.20      | 95.21              | 55                        |
| NaSO<sub>4</sub> | -             | 4.09      | 142.04             | 29                        |
| CaCl<sub>2</sub> | -             | 1.16      | 110.98             | 10                        |
| KCl        | -                   | 0.695     | 74.55              | 9                         |
| NaHCO<sub>3</sub> | -            | 0.201     | 84.01              | 2                         |
| KBr        | -                   | 0.101     | 119.00             | 1                         |
| H<sub>3</sub>BO<sub>3</sub> | -  | 0.027     | 61.83              | 0.4                       |
| SrCl<sub>2</sub> | -             | 0.0025    | 158.53             | 0.02                      |
| NaF        | -                   | 0.003     | 41.99              | 0.07                      |
| DI Water   | -                   | 988.968   | -                  | -                         |
| **Total**  | -                   | 1025      | -                  | -                         |

  + pH 7.4
  + Filter sterilize and store at 4°C

#### Dissociation Mix
##### (for embryos 2–4 dpf)
| Ingredient | Amount (µl)|
|------------|-------|
|0.25% trypsin-EDTA| 480 μl |
| Collagenase 100 mg/ml | 20 μl |

OR

##### (for embryos 5–16 dpf)
| Ingredient | Amount (µl)|
|------------|-------|
|0.25% trypsin-EDTA| 460 μl |
| Collagenase 100 mg/ml | 40 μl |

### Reagent Prep
- Resuspend the collagenase in PBS 1X (ASW?) to prepare a 100 mg/ml stock. Aliquot (40 μl each), store at −20 °C. Use a fresh aliquot for each experiment.
- Prepare DMEM-10%FBS (make fresh every time) and equilibrate at ∼30 °C. #TODO: What is ceph equivalent of DMEM-10%FBS?
- Prepare the [Dissociation Mix](#dissociation-mix) and keep at 30 °C. Each tube requires 500 μl of Dissociation Mix.


## Protocol

### Speciment Prep
1. Collect embryos or larvae at the desired stage. 
1. Euthanize embryos? and quickly proceed to the next step. 
1. <span class="critical">CRITICAL:</span> Do not freeze samples unless you are making nuclei. Freezing will destroy the cell membrane and make viable dissociation impossible.
1. Transfer embryos or larvae into 1.5 ml microcentrifuge tube   
    - ∼ 30 embryos/tube for 2–4 dpf (Adjust accordingly for ceph)
    - ∼ 20 embryos/tube 4–10 dpf
    - ∼ 5 embryos/tube 10–16 dpf
1. Wash 2X in 1 ml [ASW](#artificial-seawater-asw---cshl-protocols) 1X

### Enzymatic Dissociation
Dissociation with trypsin and collagenase

1. Remove ASW
1. Add 500 μl of [Dissociation Mix](#dissociation-mix) (pre-heated at 30 °C) to each 1.5 ml microcentrifuge tube
1. Mechanically dissociate the embryos via harsh pipetting (use a P1000 and then P200). 
    - Interval ∼30 s pipetting and ∼30 s in heat-block at 30 °C until tissue is no longer visible (5–10 min).
    - <span class="tip">NOTE:</span> once fully homogenized, the mixture will appear lighter in color.
1. Add 800 μl of DMEM-10%FBS to stop the dissociation.
1. Mix and centrifuge 5 min at 700 g at room temperature (RT)
NOTE: after centrifugation the pellet should be clearly visible.

### Preparation of single cell suspension

1. Discard the supernatant
1. Resuspend the pellet in 1 ml PBS 1X
1. Centrifuge 5 min at 700 g at RT
1. Filter single cell suspension
1. 1.Discard the supernatant and resuspend in 0.5–1 ml of DMEM-10%FBS
    - <span class="tip">NOTE:</span> If multiple samples need to be pooled for downstream applications it can be done at this resuspension step. Resuspend pellet 1 with DMEM-10%FBS and use the resuspension to resuspend subsequent samples (consider 1 ml for up to 3 samples) and then proceed to the next step.
1. Filter through 70 μm nylon mesh into 50 ml conical tube
1. Wash the filter with 500 μl of DMEM-10%FBS

Transfer the cell suspension
•
Transfer the single cell suspension into a new tube and proceed with downstream applications.
•
Optional Step: If a smaller volume is required cells can be centrifuge 5 min at 700 g at RT and resuspended in DMEM-10%FBS or a solution that downstream applications require.
CRITICAL: Keep the cell suspension at room temperature and do not store on ice.
