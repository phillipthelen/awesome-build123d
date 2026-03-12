# Awesome build123d


A curated list of [build123d](https://github.com/gumyr/build123d) code and resources. Inspired by other lists like [awesome-cadquery](https://github.com/CadQuery/awesome-cadquery).


If you want to contribute, please read [this](CONTRIBUTING.md).


## Quick Start


* [jdegenstein/build123d-portable](https://github.com/jdegenstein/build123d-portable) - A cross-platform portable build123d installation with bundled VSCode, OCP CAD Viewer, and python bundled together. Provides a quick download, unzip, and run experience -- [releases page](https://github.com/jdegenstein/build123d-portable/releases).
* [jojain/build123d-sandbox](https://github.com/jojain/build123d-sandbox) - Interactive CAD Design in the Browser - A powerful web-based sandbox for creating 3D models using Python and build123d, powered by pyodide and WebAssembly. Runs fully in your browser. Visit the live application [here](https://jojain.github.io/build123d-sandbox/).


## Editors and IDEs


* [bernhard-42/Jupyter-CadQuery](https://github.com/bernhard-42/jupyter-cadquery) - View build123d objects in JupyterLab or in a standalone viewer for any IDE.
* [bernhard-42/vscode-ocp-cad-viewer](https://github.com/bernhard-42/vscode-ocp-cad-viewer) - OCP VSCode CAD Viewer for OCP based Code-CAD (CadQuery, build123d) integrated into VS Code.
* [yeicor-3d/yet-another-cad-viewer](https://github.com/yeicor-3d/yet-another-cad-viewer) - A web-based CAD viewer for OCP models (CadQuery/build123d) that supports static site deployment. It also has a build123d playground for editing and sharing models directly in the browser ([demo](https://yeicor-3d.github.io/yet-another-cad-viewer/#pg_code_url=https://raw.githubusercontent.com/gumyr/build123d/refs/heads/dev/examples/toy_truck.py)) ![Tests](https://github.com/yeicor-3d/yet-another-cad-viewer/actions/workflows/build.yml/badge.svg?branch=master)


## Extensions and Plugins


* [bernhard-42/bd_animation](https://github.com/bernhard-42/bd_animation) - Animation class and tutorials for build123d
* [yeicor-3d/dl4to4ocp](https://github.com/yeicor-3d/dl4to4ocp) - Library that helps perform [topology optimization](https://en.wikipedia.org/wiki/Topology_optimization) on
your [OCP](https://github.com/CadQuery/OCP)-based CAD models ([CadQuery](https://github.com/CadQuery/cadquery)/[build123d](https://github.com/gumyr/build123d)/...) using the [dl4to](https://github.com/dl4to/dl4to) library.
 ![Tests](https://github.com/yeicor-3d/dl4to4ocp/actions/workflows/test.yml/badge.svg?branch=master)
* [voneiden/ocp-freecad-cam](https://github.com/voneiden/ocp-freecad-cam) CAM for CadQuery and build123d by leveraging FreeCAD library. Visualizes in CQ-Editor and ocp-cad-viewer. Spiritual successor of [cq-cam](https://github.com/voneiden/cq-cam)


## Part Libraries and Part Generators


* [experimentslabs/3d/bd_beams_and_bars](https://gitlab.com/experimentslabs/3d/bd_beams_and_bars) - Construction beams and bars - [docs](https://bd-beams-and-bars.3d.experimentslabs.com/) ![Tests](https://gitlab.com/experimentslabs/3d/bd_beams_and_bars/badges/main/pipeline.svg) 
* [experimentslabs/3d/bd_tube_boxes](https://gitlab.com/experimentslabs/3d/bd_tube_boxes) - Create boxes from old tubes - [docs](https://bd-tube-boxes.3d.experimentslabs.com)
* [GarryBGoode/py_gearworks](https://github.com/GarryBGoode/py_gearworks)  - create all kinds of gear models
* [Ruudjhuu/gridfinity_build123d](https://github.com/Ruudjhuu/gridfinity_build123d) - Create gridfinity items with build123d
* [gumyr/bd_warehouse](https://github.com/gumyr/bd_warehouse) - Augments build123d with parametric parts - generated on demand - and extensions to the core build123d capabilities.
* [keeeal/bd-vslot](https://github.com/keeeal/bd-vslot) - A library of V-Slot linear rail components - [docs](https://bd-vslot.readthedocs.io/)
* [larssont/capistry](https://github.com/larssont/capistry) - A Python package for parametric 3D modeling of keyboard keycaps using build123d
* [ndevenish/gflabel](https://github.com/ndevenish/gflabel) - Generates 3d-printable labels for gridfinity label systems
* [PaulBone/gfthings](https://github.com/PaulBone/gfthings) - A tool to generate gridfinity compatible objects like bins, grids, base edges, and pins


## Miscellaneous


* [bernhard-42/tcv_screenshots](https://github.com/bernhard-42/tcv_screenshots) - Headless screenshot generator for three-cad-viewer. Render 3D CAD models to PNG screenshots.
* [jdegenstein/build123d-f3d-render](https://github.com/jdegenstein/build123d-f3d-render) - headless automatic rendering of build123d models to PNG using f3d within CI (GitHub Actions)
* [jdegenstein/filewatcher123d](https://github.com/jdegenstein/filewatcher123d) - A file watcher oriented towards use with build123d and ocp_vscode (standalone mode, no VSCode required)
* [pzfreo/fabprint](https://github.com/pzfreo/fabprint) - Headless 3D print pipeline: arrange parts on a build plate, slice to gcode, and send to a Bambu Lab printer — all from a TOML config file. Uses build123d.![CI](https://github.com/pzfreo/fabprint/actions/workflows/ci.yml/badge.svg?branch=main)![AI-Synthesized](https://img.shields.io/badge/AI-Synthesized-blueviolet?style=flat-square "The majority of this codebase was generated using AI models based on human architectural design.")
* [Yeicor/OCP.wasm](https://github.com/Yeicor/OCP.wasm) This project ports the low-level dependencies required for build123d to run in a browser. For a fully featured frontend, check out `Yet Another CAD Viewer` (see above). ![Tests](https://github.com/Yeicor/OCP.wasm/actions/workflows/main.yml/badge.svg?branch=master)


## Examples and Projects using build123d


* [BlueDrink9/keeb_snakeskin](https://github.com/BlueDrink9/keeb_snakeskin) - Create a cool PCB case and travel case for split keyboards or other custom PCBs
* [ginkgo/trackball](https://github.com/ginkgo/trackball) - 3d-printable twist-to-scroll trackball using a Raspberry Pi Pico and two PMW3360 sensors designed using build123d
* [jgraichen/someline](https://github.com/jgraichen/someline) - 3D printable insets for some Someline® storage boxes designed using build123d
* [nicola-sorace/custom-keycap-generator](https://github.com/nicola-sorace/custom-keycap-generator) - Generate custom print-ready keycap geometries using Python and build123d
* [x0pherl/fender-bender](https://github.com/x0pherl/fender-bender) - an open-source filament buffering system for multi-material 3D printers designed using build123d


## Tutorials and Documentation


* [Official Documentation](https://build123d.readthedocs.io/en/latest/)
* [Alternate setup](https://gist.github.com/mtancoigne/9e2b7cdfb13f2c5a2a405cfb059e9b87) with `ocp_vscode`, without VSCode


## Legacy


* [BlendQuery](https://github.com/uki-dev/blendquery) - build123d integration for Blender. **(⚠️Unmaintained)**
* [KiCad Packages3D Generator](https://gitlab.com/kicad/libraries/kicad-packages3D-generator) - Python scripts for generating 3D electrical component models in STEP and VRML. 
**(⚠️Repo moved, no longer appears to use build123d)**
