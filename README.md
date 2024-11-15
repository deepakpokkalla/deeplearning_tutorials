Packages used for running these notebooks. Install miniforge and then from miniforge prompt, run the following commands to setup the environment

- conda create -n gnn_mol python==3.10
- pip install torch==2.4.0 torchvision==0.19.0 torchaudio==2.4.0 --index-url https://download.pytorch.org/whl/cu124
- pip install torch_geometric==2.6.1
- pip install matplotlib==3.9.2
- pip install pyg_lib torch_scatter torch_sparse torch_cluster torch_spline_conv -f https://data.pyg.org/whl/torch-2.4.0+cu124.html
