# Engineering application of bioinspired algorithms based on cerebellar architecture

In order to investigate bioinspired algorithms based on cerebellar architecture used for modeling mechanical systems consisting of the above basic elements, the author developed a specialized software engine in Python and JavaScript.
The basic input data for it is the definition of the number, links and properties:
- for each node - coordinates and their derivatives in time reflecting phase space parameters.
- for each spring - free distance, elasticity coefficient, resistance coefficient, numbers of bodies in the arrays that are connected by the spring.
  
The simplest constructions and the process of changing their state in time are presented below Figure 1:
<p><img src="https://www.minfo.ru/different_imgs/NaS.gif" width="600"><figcaption>Fig. 1.	Three types of simple structures and their state in time. NandS.ipynb</figcaption></p>

Behind the existing biodiversity of organic forms is 4 billion years of evolution, but for our purposes optimal solutions can be borrowed from the science of "building structures", which is also aimed at the creation and improvement of rational types of structures, but already by methods of calculation and volume-planning solutions.
For our concept, parallels can be drawn with trusses (Latin firmus "strong"), a fundamental section of structural mechanics. The task of trusses is to remain geometrically unchanged after its rigid nodes are replaced by hinge nodes; only tensile-compression forces occur in its elements, as in the case of nodes and springs. The trusses are also constructed from rectilinear rods connected at the nodes into a geometrically invariable system to which the load is applied only at the nodes .Using the above software engine we can model any truss design, Figure 2 shows four types of trusses in different gravity fields. Red color represents compression and blue color represents tension. The intensity of the color reflects the magnitude of the normalized load in the considered block.

<p><img src="https://www.minfo.ru/different_imgs/ferms.gif" width="600"><figcaption>Fig. 2.	Change in shape of trusses under different distributed loads. Ferms.ipynb</figcaption></p>

In conclusion, it should be noted that the proposed algorithm of neural network construction can be used in a wide range of applied problems, and taking into account the original bioinspired nature, its use in the construction of distributed control systems of automata and works is of particular importance. In particular, Figure 3 shows the behavior of the simplest model of a tentacle in the form of a kinematic chain, which is directly a neural network based on cerebellar architecture sensitive to external stimuli.

<p><img src="https://www.minfo.ru/different_imgs/tentacle.gif" width="900"><figcaption>Fig. 3. Tentacles in the form of a kinematic chain controlled by a neural network allows for proper positioning.</figcaption></p>
