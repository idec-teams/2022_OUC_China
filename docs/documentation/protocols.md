# Protocols

<b><font size=4>1. Strains and plasmids</b></font>

The amino acid sequence of CA was obtained from the genome sequence of Vibrio salmonicida, a strain of bacteria from the ocean.  The nucleotide sequence coding the mature enzyme was optimized for expression in E. coli BL21(DE3) and expressed using the pETDuet-1 vector that contains the ColE1 as the origin of replication, an ampicillin resistance gene as the selection marker, the T7 promoter and the lac operon. The constructed plasmid was transformed into E. coli BL21(DE3) by receptive state transformation.

<b><font size=4>2. Gene cloning and expression vector construction</b></font>

mASCA gene was amplified by PCR reaction system with 50μL solution using the synthesized mASCA gene as template. The reaction system is as follows:


|     | μL in 1 reaction | 
| :-: | :-: |
| Mix(2×) | 25μL |
| pR | 1μL |
| pF | 1μL |
| bacteria solution | 3μL |

Synthesis Pcrocess:</br>

|     | Temperature | Time | Cycle |
| :-: | :-: | :-: | :-: |
| Predenaturation | 95℃ | 5min | 1 |
| Denaturation | 95℃ | 30s | 30 |
| Annealing | 58℃ | 30s | 30 |
| Extension | 72℃ | 1min | 30 |
| Final Extension | 72℃ | 10min | 1 |
| Hold | 4℃ | ∞ |

 The PCR products were examined by electrophoresis on 1% agarose gel.

The PCR product and plasmid pETDuet-1 were purified by DNA purification kit and double digested with BamH Ⅲ and EcoR Ⅰ . The reaction system was as follows:

|     | μL in 1 reaction | 
| :-: | :-: |
| Gene | 20μL |
| 10× NB | 5μL |
| BamH Ⅲ enzyme | 1μL |
| EcoR Ⅰ enzyme | 1μL |


- Rerformed at 37℃ for 1h
- Terminated at 80℃ for 20min
- Digested products were recovered by DNA purification kit and quantified
- Products were reacted with T4 DNA ligase at room temperature for 30min or overnight at 16℃
- Transformed into competent E. coli BL21(DE3) cells
- Cultured overnight at 37℃ by LB(Amp+) screening plate


<b><font size=4>3. Determination of the activity of carbonic anhydrase</b></font>

- A single colony from the above LB(Amp+) screening plate was cultured in 100mL LB(Amp+) liquid medium for 12h
- IPTG was added to induce expression for 12h
- Lysozyme-freeze-thaw method was used to extract crude enzyme solution
    - 10ml of bacterial solution was centrifuged at 5000rpm for 5min, discarded the supernatant
    - The bacterial cells were resuspended in 0.01m PBS buffer and centrifuged at 5000rpm for 5min
    - Add 5mL of 0.01M PBS buffer and 100 μl of 20mg/mL lysozyme solution
    - React at 4℃ for 30min
    - Freeze at -80℃ for 30min and then thaw at 4℃, repeat until the thawed liquid becomes sticky obviously
    - Centrifuge at 12000rpm for 10min
    - Collect supernatant for enzyme activity determination
- Carbonic anhydrase activity was determined by p-NPA method.

</br>

Measuring the absorbance value at 348nm to calculated the enzyme activity. 

- Successively adding 5.4mL of fresh Tris buffer (100mM, pH7.6), 3mL of free enzyme, and 0.6mL of p-NPA dissolved in acetone (3mM) to a centrifuge tube.
- React for 3minthe
- Absorbance value at 348nm was measured by UV spectrophotometer, and the sample without enzyme was used as blank control. 
Relative enzyme activity was defined as the percentage of the ratio of any enzyme activity to the optimal enzyme activity under the same conditions.


<b><font size=4>4. Error prone PCR amplification</b></font>

The reaction systems with mASCA template concentrations of 1ng/μL and 10ng/μL were set as follows:

|     | μL in 1 reaction | 
| :-: | :-: |
| mASCA | 1μL |
| Mix | 3μL |
| dNTP | 3μL |
| dGTP | 2μL |
| MnCl<sub>2</sub> | 3μL |
| pR | 1μL |
| pF | 1μL |

Synthesis Pcrocess:</br>

|     | Temperature | Time | Cycle |
| :-: | :-: | :-: | :-: |
| Predenaturation | 94℃ | 3min | 1 |
| Denaturation | 94℃ | 1min | 45 |
| Annealing | 45℃ | 1min | 45 |
| Extension | 72℃ | 1min | 45 |
| Hold | 4℃ | ∞ |

The error-prone PCR products are examined by electrophoresis on 1% agarose gel.

<b><font size=4>5. Construction and of mutation libraries</b></font>

Error-prone PCR product and plasmid pETDuet-1 were purified by DNA purification kit and double digested with BamH Ⅲ and EcoR Ⅰ . The reaction system was as follows:

|     | μL in 1 reaction | 
| :-: | :-: |
| Gene | 20μL |
| 10× NB | 5μL |
| BamH Ⅲ enzyme | 1μL |
| EcoR Ⅰ enzyme | 1μL |
| ddH<sub>2</sub>O | 38μL |

Reaction was performed as follows:

- Rerformed at 37℃ for 1h
- Terminated at 80℃ for 20min
- Digested products were recovered by DNA purification kit and quantified
- Products were reacted with T4 DNA ligase at room temperature for 30min or overnight at 16℃
- Transformed into competent E. coli BL21(DE3) cells
- Cultured overnight at 37℃ by LB(Amp+) screening plate

<b><font size=4>6. Determination of enzyme activity of recombinant enzymes</b></font>

Steps are same as “Determination of the activity of carbonic anhydrase”

<b><font size=4>7. Bioinformatics analysis</b></font>

We used primers pR/pF to PCR recombinant strains exhibiting higher enzyme activity, and the PCR products were sent to Sangon Biological Company for sequencing. The gene sequence analysis and 3D structure prediction of mASCA was conducted with Phyer2 protein structure server. After finding the populations with high sequence similarity using Blastp server in NCBI, the sequences were aligned and the tree was built using the neighbor joining method in software Mega.
