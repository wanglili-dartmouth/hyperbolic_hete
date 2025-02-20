# Embedding Heterogeneous Networks into Hyperbolic Space Without Meta-path


## Requirements:
Same as https://github.com/wanglili-dartmouth/hyperbolic_struct

## Data

We use the dataset provided by the authors of HHNE (https://github.com/ydzhang-stormstout/HHNE)

DBLP dataset is inside the "data" directory 

Since MovieLens do not allow public redistribution, please contact the author of HHNE （zyd@bupt.edu.cn） if you are interested in this dataset.


## How to use

lp_ma_movie.py   link perdition task of edges between M-A in movie dataset

lp_md_movie.py	 link perdition task of edges between M-D in movie dataset

lp_pa_dblp.py    link perdition task of edges between P-A in dblp dataset

lp_pc_dblp.py    link perdition task of edges between P-C in dblp dataset

nr_ma_movie.py	 network reconstruction task of edges between M-A in movie dataset

nr_md_movie.py   network reconstruction task of edges between M-D in movie dataset

nr_pa_dblp.py    network reconstruction task of edges between P-A in dblp dataset

nr_pc_dblp.py    network reconstruction task of edges between P-C in dblp dataset

vis.py           visualization

The individual python files above require certain parameters as input. Please use run_all.sh which has the correct parameters for each lp and nr file, run_vis.sh for the visualization.

## Code reference

Our code is built on top of https://github.com/DavidMcDonald1993/heat

## Citation
```
@article{Wang_Gao_Huang_Liu_Ma_Vosoughi_2021, title={Embedding Heterogeneous Networks into Hyperbolic Space Without Meta-path}, volume={35}, number={11}, journal={Proceedings of the AAAI Conference on Artificial Intelligence}, author={Wang, Lili and Gao, Chongyang and Huang, Chenghan and Liu, Ruibo and Ma, Weicheng and Vosoughi, Soroush}, year={2021}, month={May}, pages={10147-10155} }


