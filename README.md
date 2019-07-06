# Radial Tree Layout

Author: CongVm

## Introduction

To visualize all hierachical tree of visual data, I use a tool called `radial tree`. 

Your input data is table below:

| class_id | class_name | description             | father_class_name | father_class_id |
|----------|------------|-------------------------|-------------------|-----------------|
| 1        | dog        | a Dog                   | animal            | 3               |
| 2        | cat        | a Cat                   | animal            | 3               |
| 3        | animal     | all animal on the world | object            | -1              |


And out result showed like this:

![](https://vega.github.io/vega/examples/img/radial-tree-layout.png)

## To Run

Before using this source, we need to parse the table into json following `vega format`. For more infomation, you check out `*.json`  file.

To be detail, I will update later. The source code is stored on my company PC. I forgot to upload it here all the time :((

## Reference

[1] https://vega.github.io/vega/
