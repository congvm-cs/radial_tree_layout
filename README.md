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


## Reference

[1] https://vega.github.io/vega/
