Code and data for analyzing the diversity of libraries and versions in the Maven Dependency Graph (dataset downloaded from https://zenodo.org/record/1489120)

# Requirements
* Neo4j to load the graph database
* graph algorithms for Neo4j 3.x exposed as Cypher procedures
* R version > 3.5.0 for data analysis and visualizations

# Components
 * Cypher queries for running graph based analysis and collecting data
 * R notebooks for running the calculations, getting tables and figures
 
 # Citation
 
 If you use this code, please cite the following [research paper](https://dl.acm.org/doi/10.1109/MSR.2019.00059):
 
 ```
 @inproceedings{SotoValero2019,
  title={The emergence of software diversity in maven central},
  author={Soto-Valero, C{\'e}sar and Benelallam, Amine and Harrand, Nicolas and Barais, Olivier and Baudry, Benoit},
  booktitle={2019 IEEE/ACM 16th International Conference on Mining Software Repositories (MSR)},
  pages={333--343},
  year={2019},
  organization={IEEE}
}
```
