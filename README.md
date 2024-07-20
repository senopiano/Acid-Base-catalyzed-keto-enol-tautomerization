# Acid-Base-catalyzed-keto-enol-tautomerization
Keto-enol tautomerization is a very classic type of reaction. Most of the existing DFT calculations focus on proton direct transfer mechanisms or proton transfer mediated by water molecules. However, in the reactions dominated by these two mechanisms, there are often large energy barriers to overcome. Therefore, DFT calculation of acid/base catalyzed keto-enol tautomerization is essential.
In this project, the reactant is acetone and the product is enol.
## Acid-catalyzed-keto-enol-tautomerization
The whole process includes two processes. The first step is proton transfering between acid and acetone. The second step is acetone deprotonation. The whole process is shown as below.

![image](https://github.com/senopiano/Acid-Base-catalyzed-keto-enol-tautomerization/blob/main/Acid%20mechanism.png)

After conducting the optimization of acetone and hydronium, transition state search is done. One structure is searched. However, later we did an IRC scan but the transition state is only validated as the maximum value between two conformations. Then we did flexible scanning, setting the distance between -H and -O as redundant internal coordinates. Finally we found this step doesn't have TS. Also, when we searched for the TS of the secondary step, this step doesn't have a TS either.
## Base-catalyzed-keto-enol-tautomerization
This reaction also includes two steps. The reaction mechanism is shown as below.

![image](https://github.com/senopiano/Acid-Base-catalyzed-keto-enol-tautomerization/blob/main/Base%20mechanism.png)
