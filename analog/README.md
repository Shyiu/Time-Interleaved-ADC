# Folder Structure 
```
analog/
├── blocks/
│   ├── cell/ 
│   │   ├── cell.xschem
│   │   ├── cell.gds
│   │   └── sim/
│   │       ├── tb_cell.xschem
│   │       └── tb_cell.spice
|   └── another_cell/
│       ├── another_cell.xschem
│       ├── another_cell.gds
│       └── sim/
│           ├── tb_another_cell.xschem
│           └── tb_another_cell.spice
├── top/
│   └── top.gds
│   └── top.lef
|   └── sim/
│       └── tb_top.xschem
│       └── tb_top.spice
└── README.md
````

## blocks/
Individual circuit blocks, each self-contained with schematic, layout, and simulation testbench.

## top/
Full assembled design connecting all blocks, with final GDS and LEF for handoff.
