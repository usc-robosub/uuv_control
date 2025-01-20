# uuv_control

A set of ROS packages

- For AUVs
    - [`casadi`](https://web.casadi.org/)-based effort allocation algorithm 
    - Geometric tracking PD controller
- For ROVs
    - Thruster manager with computation of the thruster allocation matrix based on the thruster frames available in `/tf`
    - Model-based feedback linearization controller ([`Fossen, 2011`](https://www.wiley.com/en-us/Handbook+of+Marine+Craft+Hydrodynamics+and+Motion+Control-p-9781119991496))
    - Nonlinear PID controller ([`Fossen, 2011`](https://www.wiley.com/en-us/Handbook+of+Marine+Craft+Hydrodynamics+and+Motion+Control-p-9781119991496))
    - Non-model-based sliding mode controller ([`García-Valdovinos el al., 2014`](https://journals.sagepub.com/doi/full/10.5772/56810) and [`Salgado-Jiménez et al., 2011`](http://cdn.intechopen.com/pdfs/15221.pdf))
    - PD controller with restoration forces compensation 
    - 6-DOF PID controller
    - Singularity-free tracking controller ([`Fjellstad and Fossen, 1994`](https://ieeexplore.ieee.org/abstract/document/411068))
- Teleoperation nodes for AUVs and ROVs

```
@inproceedings{Manhaes_2016,
	doi = {10.1109/oceans.2016.7761080},
	url = {https://doi.org/10.1109%2Foceans.2016.7761080},
	year = 2016,
	month = {sep},
	publisher = {{IEEE}},
	author = {Musa Morena Marcusso Manh{\~{a}}es and Sebastian A. Scherer and Martin Voss and Luiz Ricardo Douat and Thomas Rauschenbach},
	title = {{UUV} Simulator: A Gazebo-based package for underwater intervention and multi-robot simulation},
	booktitle = {{OCEANS} 2016 {MTS}/{IEEE} Monterey}
}
```

> Link to the `uuv_simulator` repository [here](https://github.com/uuvsimulator/uuv_simulator)

> Link to the [documentation page](https://uuvsimulator.github.io/packages/uuv_simulator/intro/) 