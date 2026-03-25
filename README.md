# NOA Toolbox Demonstration

## General Description

The NOA Toolbox is a Matlab Toolbox developed by Rexys, a canadian company from Montreal, specialized in advanced FPGA development and embedded electronics.

It enables engineering teams to translate Simulink models into deterministic FPGA implementations on hardware, especially the NOA Arch1 FPGA platform, without low-level HDL development.

This Github repository is a public project, dedicated to example designs made on Matlab Simulink, using the NOA Toolbox. It was developed in the context of an internship at Rexys, along with the toolbox documentation, to complete it and show concretly how NOA Toolbox could be used.

The toolbox documentation is available at:

<https://docs.rexys.io/Toolbox/index.html>

For more details on Rexys, go to:

<https://rexys.io/>

## Dependencies

These Simullink projects were made on Matlab R2025a, using Rexys' NOA Toolbox and Vivado 2024.1. They also require the HDL Coder Add-On.

## Structure

/demos_github_NOA
├── /example_projects                       #Simulink files of example projects
│   ├── /sinus_generator
│   │   └── sine_gen_v1.slx
│   └── /three_phase_generators
│       ├── sine_gen_triphase_v1.slx
│       ├── sine_gen_triphase_v2.slx
│       └── sine_gen_triphase_v3.slx
└── README.md                               #this file

## Content

* `sinus_generator`: a design generating a sine wave with adjustable frequency and amplitude

* `three_phase_generators`: three versions of a design generating three sine waves with adjustable frequency and amplitude

## Authors

Ambre Brifflot