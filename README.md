### I. Prerequisites

1. Download and install Anaconda (Download link: https://www.anaconda.com/).

2. Download the code compressed package hainanhof_interactive.zip (Download link:https://github.com/wchou93/hainanhof_interactive).

3. Create a folder at any location (e.g., a "Jupyter" folder on your desktop), place the compressed package into it, and extract the contents.

### II. Usage Instructions

1. Open Anaconda Navigator, select Jupyter Lab, and start it.

2. On the left side of the popped-up Jupyter Lab web window, find the path where the hainanhof_interactive folder was placed. Open it, and you will see several files such as database_HOF.py.

3. Click the blue "+" icon in the upper left corner, select "python3 (ipykernel)" under the first Notebook option, and a new window will pop up.

4. Enter %run database_HOF.py. If -Load Done- appears after running, it means the program has been successfully launched, and you can start querying and making predictions.

5. Input the compound name, CAS number, or SMILES expression to query existing synthesis schemes in the database. Additionally, you can predict the dosage ratio of ligands, the name and dosage of solvents, as well as the properties of additives, temperature, and time parameters，and the final prediction scheme will appear in the Excel table named "output_schemes" in this compressed package.

**Example Input** **:** Can you output the synthesis schemes for HOF using 4,4'-bipyridine as one of the ligands?

**System Output:**  

```
Synthesis Method 1:
 
Synthesis of HOF. As shown in Scheme 1, Suzuki−Miyaura cross-coupling reaction of pinacol boronate derivative 1 and 4,7-dibromobenzo[c][1,2,5]thiadiazole (2) gave dicarboxylbenzothiadiazole derivative 3. Hydrolysis of 3 in the presence of KOH gave tetracarboxylic acid 5′,5″″-[benzo[c][1,2,5]thiadiazole-4,7-diyl)bis(([1,1′:3′,1″-terphenyl]-4,4″-dicarboxylic acid)] BTTA, which was characterized by 1H and 13C NMR spectroscopy and high-resolution mass spectrometry. The synthesized BTTA was recrystallized by slow evaporation of a mixed solution of N,N-dimethylformamide (DMF) and 1,2,4-trichlorobenzene (TCB) at 70 °C to give solvent-included HOF BTTA-1(TCB) as needle- or column-shaped crystals with typical dimensions of 30 μm × 20 μm × 15 μm (Figure S1).。
 
For more details, see:
nan
 
 
----------------------------------------
 
Synthesis Method 2:
 
The upconversion crystalline HOF was prepared by crystallization through coprecipitation of PtOEP and DPACOOH (1/2 500) from N, N-diethylformamide into water.。
 
For more details, see:https://doi.org/10.
 
 
----------------------------------------
 
Synthesis Method 3:
 
Exfoliation of the 1D Nanoribbon (nr-HOF): In a typical experiment, 6 mg of bulk precursor TCPP-1,3-DPP was dispersed in 30 mL of deionized water. The mixture was then sonicated in an ultrasonic bath (Brandson, CPX2800H-E, 110 W, 40 kHz) for 30 min, followed by vigorous stirring for 12 h. After that, a milky colloidal suspension was obtained without any sedimentation. The powdered samples of the 1D nanoribbons nr-HOF were collected by freeze-drying for further applications. Elem anal. Calcd: C, 74.08; H, 4.84; N, 8.49. Found: C, 73.99; H, 4.75; N, 8.48.。
 
For more details, see:
nan
 
 
----------------------------------------
 
Synthesis Method 4:
 
Herein, we systematically synthesized HOF using amidinium and carboxylate functional groups containing building blocks that could self-assemble in aqueous solutions, with porous crystalline networks through charge-assisted hydrogen bonds. We used tetraamidinium (1·Cl4) and tetracarboxylate (2) as building blocks for HOF synthesis. The one-pot synthesis method was employed to encapsulate single and bi-enzyme systems during HOF crystal formation, resulting in GOx@HOF and GOx-HRP@HOF composites. This synthesis process was carried out under ambient conditions, allowing for the in-situ encapsulation of enzymes while maintaining their activity.。
 
For more details, see:https://doi.org/10.1002/chem.202401256
 
 
----------------------------------------
 
Synthesis Method 5:
 
CP-Py was, furthermore, crystallized using other aromatic solvents, such as 1,2,4-trichlorobenzene (TCB) and N,N-dimethylaniline (DMAni) to yield the corresponding solvated HOFs CP-Py-1 (TCB) and CP-Py-1 (DMAni) with host/guest ratio of 1:4 (Fig. S8–S11, ESI † ).。
 
For more details, see:https://doi.org/10.1039/d3cc01877f
 
```



```
Synthesis Method 1:
 
Synthesis of HOF. As shown in Scheme 1, Suzuki−Miyaura cross-coupling reaction of pinacol boronate derivative 1 and 4,7-dibromobenzo[c][1,2,5]thiadiazole (2) gave dicarboxylbenzothiadiazole derivative 3. Hydrolysis of 3 in the presence of KOH gave tetracarboxylic acid 5′,5″″-[benzo[c][1,2,5]thiadiazole-4,7-diyl)bis(([1,1′:3′,1″-terphenyl]-4,4″-dicarboxylic acid)] BTTA, which was characterized by 1H and 13C NMR spectroscopy and high-resolution mass spectrometry. The synthesized BTTA was recrystallized by slow evaporation of a mixed solution of N,N-dimethylformamide (DMF) and 1,2,4-trichlorobenzene (TCB) at 70 °C to give solvent-included HOF BTTA-1(TCB) as needle- or column-shaped crystals with typical dimensions of 30 μm × 20 μm × 15 μm (Figure S1).。
 
----------------------------------------
 
Synthesis Method 2:
 
The upconversion crystalline HOF was prepared by crystallization through coprecipitation of PtOEP and DPACOOH (1/2 500) from N, N-diethylformamide into water.。
 
----------------------------------------
 
Synthesis Method 3:
 
Exfoliation of the 1D Nanoribbon (nr-HOF): In a typical experiment, 6 mg of bulk precursor TCPP-1,3-DPP was dispersed in 30 mL of deionized water. The mixture was then sonicated in an ultrasonic bath (Brandson, CPX2800H-E, 110 W, 40 kHz) for 30 min, followed by vigorous stirring for 12 h. After that, a milky colloidal suspension was obtained without any sedimentation. The powdered samples of the 1D nanoribbons nr-HOF were collected by freeze-drying for further applications. Elem anal. Calcd: C, 74.08; H, 4.84; N, 8.49. Found: C, 73.99; H, 4.75; N, 8.48.。
 
----------------------------------------
 
Synthesis Method 4:
 
Herein, we systematically synthesized HOF using amidinium and carboxylate functional groups containing building blocks that could self-assemble in aqueous solutions, with porous crystalline networks through charge-assisted hydrogen bonds. We used tetraamidinium (1·Cl4) and tetracarboxylate (2) as building blocks for HOF synthesis. The one-pot synthesis method was employed to encapsulate single and bi-enzyme systems during HOF crystal formation, resulting in GOx@HOF and GOx-HRP@HOF composites. This synthesis process was carried out under ambient conditions, allowing for the in-situ encapsulation of enzymes while maintaining their activity.。
 
For more details, see:https://doi.org/10.1002/chem.202401256
 
 
----------------------------------------
 
Synthesis Method 5:
 
CP-Py was, furthermore, crystallized using other aromatic solvents, such as 1,2,4-trichlorobenzene (TCB) and N,N-dimethylaniline (DMAni) to yield the corresponding solvated HOFs CP-Py-1 (TCB) and CP-Py-1 (DMAni) with host/guest ratio of 1:4 (Fig. S8–S11, ESI † ).。
 
For more details, see:https://doi.org/10.1039/d3cc01877f
 
```

 



**Example Input**: I want to Synthesize HOF，using two ligands with CAS number 807-19-2 and 108-78-1.Please predict the solvent name and dosage,and generate 10 divergent schemes.

**System Output**:

| **Prediction** | **Ligand1 (weight)** | **Ligand2 (weight)** | **Ligand_ratio** | **Solvent**               | **Amount**               | **Solvent_ratio** | **Additive System** | **Temperature (K)** | **Time (h)** |
| -------------- | -------------------- | -------------------- | ---------------- | ------------------------- | ------------------------ | ----------------- | ------------------- | ------------------- | ------------ |
| V1             | 8.590  mmol          | 16.030  mmol         | 1:1.9            | n-BuOH                    | 2.63ml                   | /                 | none                | 375.78              | 65.07        |
| V2             | 0.160  mmol          | 1.440  mmol          | 1:9              | n-BuOH                    | 3.74ml                   | /                 | none                | 375.86              | 65.72        |
| V3             | 12.860  mmol         | 17.980  mmol         | 1:1.4            | DMF                       | 3.92ml                   | /                 | none                | 376.48              | 64.92        |
| V4             | 1.000  mmol          | 2.160  mmol          | 1:2.2            | THF   DMF   O-DCB         | 3.73ml   3.93ml   1.99ml | 1:1.1:0.5         | none                | 375.79              | 65.71        |
| V5             | 0.080  mmol          | 5.040  mmol          | 1:63             | Dioxane   MeOH            | 4.01ml   3.3ml           | 1:0.8             | none                | 375.65              | 64.93        |
| V6             | 12.860  mmol         | 17.620  mmol         | 1:1.4            | THF   Mesitylene   n-BuOH | 3.66ml   3.99ml   1.19ml | 1:1.1:0.3         | none                | 376.27              | 55.39        |
| V7             | 1.100  mmol          | 1.460  mmol          | 1:1.3            | n-BuOH                    | 3.91ml                   | /                 | none                | 388.26              | 64.91        |
| V8             | 1.000  mmol          | 5.100  mmol          | 1:5.1            | Mesitylene                | 3.16ml                   | /                 | none                | 375.79              | 65.07        |
| V9             | 13.450  mmol         | 17.690  mmol         | 1:1.3            | DMF                       | 2.96ml                   | /                 | none                | 375.57              | 55.31        |
| V10            | 9.430  mmol          | 16.250  mmol         | 1:1.7            | Dioxane                   | 2.8ml                    | /                 | none                | 376.08              | 65.57        |

 

Click to add a cell.

 



 

### III. Frequently Asked Questions

To stop the query: In Jupyter, click Kernel → Restart to restart the kernel.

 
