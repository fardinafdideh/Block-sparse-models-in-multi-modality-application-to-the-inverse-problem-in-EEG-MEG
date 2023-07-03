# Block-sparse Models in Multi-modality: Application to the Inverse Problem in EEG/MEG
**Abstract:** Many natural phenomena are too complex to be fully recognised by only a single measurement instrument or mono-modality. Therefore, the research domain of multi-modality has emerged to better identify the rich characteristics of the natural multi-property phenomenon, through jointly analysing the data collected from mono-modalities, which are somehow complementary. In our study, the multi-property phenomenon of interest is the human brain activity and we are interested in better localising it by means of its electromagnetic properties which are measurable non-invasively. In neurophysiology, a common way to measure the electric and magnetic properties of the brain activity is ElectroEncephaloGraphy (EEG), and MagnetoEncephaloGraphy (MEG), respectively. Our real-world application, i.e., EEG/MEG source reconstruction problem, is a fundamental problem in neuroscience ranging from cognitive science to neuropathology to surgical planning. Considering that the EEG/MEG source reconstruction problem can be reformulated as an underdetermined system of linear equations, the solution (estimated brain source activity) should be sufficiently sparse in order to be recovered uniquely. The amount of sparsity is determined by the so-called recovery conditions. However, in high-dimensional problems, the conventional recovery conditions are extremely strict. By regrouping the coherent columns of a dictionary, the more incoherent structure could be achieved. This strategy was proposed as a block structure identification framework, which results in the automatic segmentation of the brain source space, without using any information about the brain sources activity and EEG/MEG signals. Despite the resulted less coherent block-structured dictionary, the conventional recovery condition is no longer capable of computing the coherence characterisation. To address the mentioned challenge, the general framework of block-sparse exact recovery conditions including three theoretical and one algorithmic-dependent conditions was proposed. Finally, we investigated the EEG and MEG multi-modality and demonstrated that by combining the two modalities, more refined brain regions appeared.

**Keywords:** $({q,p})$-Block Mutual Coherence Constant (Block-MCC ${q,p}$), Block Null Space Property (Block-NSP), Block-Spark, Block-sparse Exact Recovery Conditions (Block-ERC), block-sparse uncertainty principle, Block-sparsity, block structure identification, brain source space segmentation, cumulative Block-MCC ${q,p}$, EEG and MEG multi-modality.

# Des Modèles Bloc-parcimonieux en Multi-modalité : Application au Problème Inverse en EEG/MEG
**Résumé :** De nombreux phénomènes naturels sont trop complexes pour être pleinement reconnus par un seul instrument de mesure ou par une seule modalité. Par conséquent, le domaine de recherche de la multi-modalité a émergé pour mieux identifier les caractéristiques riches du phénomène naturel de la multi-propriété naturelle, en analysant conjointement les données collectées à partir d’uniques modalités, qui sont en quelque sorte complémentaires. Dans notre étude, le phénomène d'intérêt multi-propriétés est l'activité du cerveau humain et nous nous intéressons à mieux la localiser au moyen de ses propriétés électromagnétiques, mesurables de manière non invasive. En neurophysiologie, l'électroencéphalographie (EEG) et la magnétoencéphalographie (MEG) constituent un moyen courant de mesurer les propriétés électriques et magnétiques de l'activité cérébrale. Notre application dans le monde réel, à savoir le problème de reconstruction de source EEG / MEG, est un problème fondamental en neurosciences, allant des sciences cognitives à la neuropathologie en passant par la planification chirurgicale. Considérant que le problème de reconstruction de source EEG / MEG peut être reformulé en un système d'équations linéaires sous-déterminé, la solution (l'activité estimée de la source cérébrale) doit être suffisamment parcimonieuse pour pouvoir être récupérée de manière unique. La quantité de parcimonie est déterminée par les conditions dites de récupération. Cependant, dans les problèmes de grande dimension, les conditions de récupération conventionnelles sont extrêmement strictes. En regroupant les colonnes cohérentes d'un dictionnaire, on pourrait obtenir une structure plus incohérente. Cette stratégie a été proposée en tant que cadre d’identification de structure de bloc, ce qui aboutit à la segmentation automatique de l’espace source du cerveau, sans utiliser aucune information sur l’activité des sources du cerveau et les signaux EEG / MEG. En dépit du dictionnaire structuré en blocs moins cohérent qui en a résulté, la condition de récupération conventionnelle n’est plus en mesure de calculer la caractérisation de la cohérence. Afin de relever le défi mentionné, le cadre général des conditions de récupération exactes par bloc-parcimonie, comprenant trois conditions théoriques et une condition dépendante de l'algorithme, a été proposé. Enfin, nous avons étudié la multi-modalité EEG et MEG et montré qu'en combinant les deux modalités, des régions cérébrales plus raffinées sont apparues.

**Mots clés :** $({q,p})$-constante cohérence mutuelle par bloc, propriété null space par bloc, bloc-spark, conditions de reconstruction exacte par bloc-parcimonieux, Principe d'incertitude par bloc-parcimonieux, bloc-parcimonieux, identification de la structure de bloc, segmentation spatiale de l’activité cérébrale, $({q,p})$-constante cohérence mutuelle cumulée par bloc, multimodalité en EEG et MEG.

## Theoretical and Algorithmic Block-sparsity Level: MATLAB-based Toolbox Developed for Numerical Simulations
The following last three slides explain the algorithms used for the numerical simulations.
![](/ppt/BlockSparsityNumericalSimulation.gif)

## LeadField-based Brain Parcellation using Block-MCC
For further details, please visit [here](https://github.com/fardinafdideh/LeadField-based-Brain-Parcellation/tree/main).
![](/ppt/average-2,2.gif)

## Electric, Magnetic, and ElectroMagnetic Properties of a Probe Dipole (Planar Simulation)
* Angle and Amplitude of a Probe Dipole in a 2D Plane (Source Space) in Order Have the Same ElectroMagnetic Effects Captured by Two Sensors on the Same Plane.
![](/ppt/twoDimSourceTwoSensor-SameSurface.png)

## Electric, and Magnetic Effects of a Probe Dipole (Planar Simulation)
* Electric Potential and Magnetic Field of a Probe Dipole (Fixed Amplitude, Varying Angle) Captured by Two Sensors on the Same Plane.
![](/ppt/ElectroMagneticDipole.png)
![](/ppt/ElectroMagneticDipole.gif)

## Single Dipole Reconstruction (Planar Simulation)
* Single Dipole (Fixed Amplitude and Angle) Reconstruction using Three Electric and Magnetic Sensors Located in Varying Locations When the Source and Sensor Spaces are Planar.
![](/ppt/twoDimSourceSensor-twoSurfaces.png)
![](/ppt/twoDimSourceSensor-twoSurfaces.gif)

* Single Dipole (Fixed Amplitude, Varying Angle) Reconstruction (Different Methods) using Two Electric, Magnetic, and ElectroMagnetic Sensors.
![](/ppt/ElectroMagneticSourceReconstruction.gif)

## Geometrical Interpretation of the Proposed Dictionary Characteristic using a Toy Example
![](/ppt/BMCC-geometrical.png)

## Block-sparse Models in Multi-modality: Application to the Inverse Problem in EEG/MEG
![Slide1](/ppt/Slide1.PNG)
![Slide2](/ppt/Slide2.PNG)
![Slide3](/ppt/Slide3.PNG)
![Slide4](/ppt/Slide4.PNG)
![Slide5](/ppt/Slide5.PNG)
![Slide6](/ppt/Slide6.PNG)
![Slide7](/ppt/Slide7.PNG)
![SlideLF](/ppt/LF.gif)
![Slide8](/ppt/Slide8.PNG)
![Slide9](/ppt/Slide9.PNG)
![Slide10](/ppt/Slide10.PNG)
![Slide11](/ppt/Slide11.PNG)
![Slide12](/ppt/Slide12.PNG)
![Slide13](/ppt/Slide13.PNG)
![Slide14](/ppt/Slide14.PNG)
![Slide15](/ppt/Slide15.PNG)
![Slide16](/ppt/Slide16.PNG)
![Slide17](/ppt/Slide17.PNG)
![Slide18](/ppt/Slide18.PNG)
![Slide19](/ppt/Slide19.PNG)
![Slide20](/ppt/Slide20.PNG)
![Slide21](/ppt/Slide21.PNG)
![Slide22](/ppt/Slide22.PNG)
![Slide23](/ppt/Slide23.PNG)
![Slide24](/ppt/Slide24.PNG)
![Slide25](/ppt/Slide25.PNG)
![Slide26](/ppt/Slide26.PNG)
![Slide27](/ppt/Slide27.PNG)
![Slide28](/ppt/Slide28.PNG)
![Slide29](/ppt/Slide29.PNG)
![Slide30](/ppt/Slide30.PNG)
![Slide31](/ppt/Slide31.PNG)
![Slide32](/ppt/Slide32.PNG)
![Slide33](/ppt/Slide33.PNG)
![Slide34](/ppt/Slide34.PNG)
![Slide35](/ppt/Slide35.PNG)
![Slide36](/ppt/Slide36.PNG)
![Slide37](/ppt/Slide37.PNG)
![Slide38](/ppt/Slide38.PNG)
![Slide39](/ppt/Slide39.PNG)
![Slide40](/ppt/Slide40.PNG)
![Slide41](/ppt/Slide41.PNG)
![Slide42](/ppt/Slide42.PNG)
![](/ppt/Slide43.PNG)

## Algoritms used in the Numerical Simulations Toolbox 
![](/ppt/Diapositive1.PNG)
![](/ppt/Diapositive2.PNG)
![](/ppt/Diapositive3.PNG)

# How to cite
* **F. Afdideh**, R. Phlypo, C. Jutten, “Recovery guarantees for mixed norm $\ell_{p_1,p_2}$ block sparse representations,” 24th European Signal Processing Conference ([EUSIPCO](https://ieeexplore.ieee.org/document/7760274)), pp. 378-382, Sep. 2016.
* **F. Afdideh**. Block-sparse models in multi-modality: application to the inverse model in EEG/MEG. Signal and Image Processing. [Université Grenoble Alpes](https://theses.hal.science/tel-02024666), 2018. English. NNT : 2018GREAT074. tel-02024666
* **F. Afdideh**, R. Phlypo, C. Jutten, “Exact Recovery Conditions for Optimally Block-sparse Representation in General Dictionaries via General $\ell^w_{p_1,p_2}$ Weighted (Pseudo-)Mixed-norm Minimization,” [in preparation](https://github.com/fardinafdideh/Exact-Recovery-Conditions-for-Optimally-Block-sparse-Representation-in-General-Dictionaries-).
* **F. Afdideh**, R. Phlypo, C. Jutten, “An Overview of Exact and Stable Recovery Conditions for Optimally Sparse and Block-sparse Representation,” [in preparation](https://github.com/fardinafdideh/Exact-Recovery-Conditions-for-Optimally-Block-sparse-Representation-in-General-Dictionaries-).
* **F. Afdideh**, R. Phlypo, C. Jutten, “LeadField-based Brain Source Space Parcellation using a Block-sparse Metric and Hierarchical Clustering,” [in preparation](https://github.com/fardinafdideh/LeadField-based-Brain-Parcellation/tree/main).
