### -> submitter ORCID (or name)

0000-0001-7919-2575

### -> slug

Jie-2025-granulites

### -> license

CC-BY-4.0

### -> alternative license URL

_No response_

### -> model category

model published in study

### -> model status

completed

### -> associated publication DOI

http://doi.org/10.1016/j.epsl.2025.119681

### -> model creators

0000-0001-7919-2575

### -> title

_No response_

### -> description

This model was developed to test the generation of non-orogenic granulites due to rifting. We implemented a melt generation and emplacement model and compared with analytical results obtained from the Fraser zone, SW WA.

### -> abstract

Mesoproterozoic orogens are unusual in that they commonly preserve a record of high geothermal gradients, low crustal thickness, and limited topography. One such terrane is the Fraser Zone in the Albany–Fraser Orogen (AFO), Western Australia, where granulite-facies rocks record a counterclockwise pressure–temperature (CCW $P–T$) evolution, the drivers of which remain the subject of debate. To understand how the Fraser Zone reached high temperatures followed by burial, a new geochronological and petrological dataset from a metamorphosed gabbronorite was collected. This data places direct temporal constraints on the up-pressure section of the CCW $P–T$ evolution. The gabbronorite preserves an original cumulate texture that crystallised at $\sim 6\ \text{kbar}$ and $\sim 810^{\circ}\text{C}$ that partially recrystallised at conditions of $\sim 9.5\ \text{kbar}$ and $850{-}950^{\circ}\text{C}$, as constrained by conventional thermobarometers and pseudosection modelling. Zircon grains with distinct textural and geochemical characteristics constrain the timing of emplacement, melt crystallisation at $1288 \pm 7\ \text{Ma}$, and subsequent up-pressure recrystallisation at $1284 \pm 7\ \text{Ma}$. These combined $P–T$ and geochronological constraints define a rapid burial path to $\sim 12\ \text{km}$ within $c.\ 4\ \text{Myr}$ of initial crystallisation, requiring a re-evaluation of the previous models involving collision and thickening as the timing of the up-pressure excursion pre-dates the established timing of collision between the Western Australian and South Australian Cratons. Thermomechanical geodynamic modelling elucidates a viable tectonic setting for the generation of the granulites of the Fraser Zone, involving rift foundering triggered by asymmetric extension in the backarc that was terminated by subsequent arc advance. Globally, a similar mechanism may have resulted in the ubiquitous high thermobaric ratio metamorphism, low crustal thickness, and limited elevation, associated with the Mesoproterozoic metamorphic record associated with the assembly of Rodinia.


### -> scientific keywords

granulites, melt, emplacement

### -> funder

https://ror.org/05mmh0f86, FT220100566

### -> model embargo?

_No response_

### -> include model code ?

- [x] yes

### -> model code/inputs DOI

_No response_

### -> model code/inputs notes

Model is setup with a python script
Models require underworld2 to be run

### -> include model output data?

- [x] yes

### -> data creators

_No response_

### -> model output data DOI

_No response_

### -> model output data notes

output is primarily h5 files, with 139 timesteps saved. ~8.18 GB of data.

### -> model output data size

~8.18 GB of data.

### -> software framework DOI/URI

https://zenodo.org/records/6820562

### -> software framework source repository

https://github.com/underworldcode/underworld2

### -> name of primary software framework (e.g. Underworld, ASPECT, Badlands, OpenFOAM)

underworld2

### -> software framework authors

_No response_

### -> software & algorithm keywords

python, finite element, particle in cell

### -> computer URI/DOI

https://doi.org/10.48569/18sb-8s43

### -> add landing page image and caption

[Model_evolution.pdf](https://github.com/user-attachments/files/23468159/Model_evolution.pdf)

Evolution of model at selected timesteps, showing the melt generation and emplacement.

### -> add an animation (if relevant)

https://github.com/user-attachments/assets/ab1c6548-fab2-42ad-bd5c-b0d78f670bb7

Model evolution showing the generation and emplacement of melt during rifting.


### -> add a graphic abstract figure (if relevant)

_No response_

### -> add a model setup figure (if relevant)

[Model_setup.pdf](https://github.com/user-attachments/files/23468175/Model_setup.pdf)

Model setup, showing the initial geotherm and material distribution.

### -> add a description of your model setup

The 2D model is designed to simulate extension and the emplacement of melt in the crust. The model has a length (x) of 660 km and a height (y) of 140 km. The grid is uniformly spaced at 330 x 70 nodes, producing a grid resolution of 2 km, with 30 particles per cell to track material properties. The model is layered, with a 20 km thick upper crust and 20 km thick lower crust, 80 km thick lithospheric mantle and 10 km thick asthenosphere. A Gaussian plastic strain distribution is initially prescribed across the crust and lithospheric mantle localises deformation and promotes the thinning of the crust during extension. A constant temperature (T = 20 °C) is applied to the top boundary, with no heat flux across the side walls. A Moho temperature of 700 °C is prescribed at a depth of 40 km, which results in a geotherm 17 °C/km across the crust. The lithosphere-asthenosphere temperature is 1375 °C at a depth of 120 km, which is a geothermal gradient of 8.4375 °C/km across the lithosphere. In the asthenosphere, a 0.4 °C/km adiabatic gradient is prescribed, resulting in a temperature of 1380 °C at the bottom of the domain.

### Please provide any feedback on the model submission process? 

_No response_