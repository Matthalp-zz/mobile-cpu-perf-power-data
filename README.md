## Generation Mobile CPU Performance and Power Data

## Conditions of Use

Cite the [paper](http://ieeexplore.ieee.org/document/7446054/) whenever you use this data in any publication or presentation.

The BiBTex is provided below for convenience:

```
@inproceedings{halpern2016mobile,
  title={Mobile CPU’s Rise to Power: Quantifying the Impact of
         Generational Mobile CPU Design Trends on Performance,
         Energy, and User Satisfaction},
  author={Halpern, Matthew and
          Zhu, Yuhao and
          Janapa Reddi, Vijay},
  booktitle={High Performance Computer Architecture (HPCA),
             2016 IEEE 22nd International Symposium on},
  year={2016}
}
```

### Introduction

The data in this spreadsheet is a companion to the paper:

M. Halpern, Y. Zhu, V. J. Reddi, **"Mobile CPU's Rise to Power: Quantifying the Impact of Generational Mobile CPU Design Trends on Performance, Energy, and User Satisfaction"**, in the 22nd
Symposium on High Performance Computer Architecture (HPCA), March, 2016.

The data can be found within the following three CSV files:

### phones.csv

| Column       | Description                                     |
|--------------|-------------------------------------------------|
| phone_id     | Unique identifier for phone studied             |
| manufacturer | Phone manufacturer                              |
| model        | Phone model name                                |
| soc          | System-on-Chip                                  |
| process      | Process technology node                         |
| cpu          | CPU design                                      |
| cores        | Number of CPU cores (big/LITTLE when necessary) |
| frequency    | Peak CPU operating frequency (we observed)      |
| l0_cache     | L0 cache size (instruction/data)                |
| l1_cache     | L1 cache size (instruction/data)                |
| l2_cache     | L2 cache size (instruction/data)                |
| ram          | DRAM size and technology                        |
| os           | Android OS version                              |

### perf.csv

| Column       | Description                                  |
|--------------|----------------------------------------------|
| phone_id     | Unique identifier for phone studied          |
| spec         | SPEC execution time                          |
| coremark     | Coremark execution time                      |
| sunspider    | Sunspider execution time                     |
| geekbench    | Geekbench execution time                     |
| stream       | Stream execution time                        |

### power.csv

| Column       | Description                                  |
|--------------|----------------------------------------------|
| phone_id     | Unique identifier for phone studied          |
| spec         | SPEC average power consumption               |
| coremark     | Coremark average power consumption           |
| sunspider    | Sunspider average power consumption          |
| geekbench    | Geekbench average power consumption          |
| stream       | Stream average power consumption             |

## Methodology

Experimental methodology details for the performance experiments and power
measurements can be found in Sections 2.1  and 2.1, respectively, within the [paper](http://ieeexplore.ieee.org/document/7446054/).
