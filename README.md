# Acid-Base-catalyzed-keto-enol-tautomerization
Keto-enol tautomerization is a very classic type of reaction. Most of the existing DFT calculations focus on proton direct transfer mechanisms or proton transfer mediated by water molecules. However, in the reactions dominated by these two mechanisms, there are often large energy barriers to overcome. Therefore, DFT calculation of acid/base catalyzed keto-enol tautomerization is essential.
In this project, the reactant is acetone and the product is enol.
## Acid-catalyzed-keto-enol-tautomerization
The whole process includes two processes. The first step is proton transfering between acid and acetone. The second step is acetone deprotonation. The whole process is shown as below.

After conducting the optimization of acetone and hydronium, transition state search is done. One structure is searched. However, later we did an IRC scan but the transition state is only validated as the maximum value between two conformations. Then we did flexible scanning, setting the distance between -H and -O as redundant internal coordinates. Finally we found this step doesn't have TS.
