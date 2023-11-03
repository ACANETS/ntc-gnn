# ntc-gnn
The repository document the source code of the following works:
- Huoh, Ting-Li, et al. "Flow-based encrypted network traffic classification with graph neural networks." *IEEE Transactions on Network and Service Management* (2022).
- Huoh, Ting-Li, Yan Luo, and Tong Zhang. "Encrypted network traffic classification using a geometric learning model." *2021 IFIP/IEEE International Symposium on Integrated Network Management (IM).* IEEE, 2021.
## Getting started
- GNN_model.ipynb
>This file provides the GNN training pipelline from loading the data into a graph to train and validate the GNN.
- preprocessing_function.ipynb
> This file provides the function for preprocessing a .pcap file.
## Prerequisites
- [Graph Nets library](https://github.com/google-deepmind/graph_nets)
- tensorflow 2.2.0
- numpy 1.18.1
- scipy 1.4.1
- cuda 10.1
## Dataset
VPN-nonVPN dataset (ISCXVPN2016): [https://www.unb.ca/cic/datasets/vpn.html](https://www.unb.ca/cic/datasets/vpn.html)
## Cite
> Access our journal paper [here](https://ieeexplore.ieee.org/abstract/document/9979671?casa_token=yO7ubB9n8BsAAAAA:tnWRktbcQ_ocsT3ahvr8mXJaQqm2MhrWc9DCu2rlhcadIBNMG5q4Jln_X4gSGj9jnUfXvpQ5):
- **Flow-based encrypted network traffic classification with graph neural networks**
```
@article{huoh2022flow,
  title={Flow-based encrypted network traffic classification with graph neural networks},
  author={Huoh, Ting-Li and Luo, Yan and Li, Peilong and Zhang, Tong},
  journal={IEEE Transactions on Network and Service Management},
  year={2022},
  publisher={IEEE}
}
```
***
> Access our conference paper [here](https://ieeexplore.ieee.org/abstract/document/9463930):
- **Encrypted network traffic classification using a geometric learning model**
```
@inproceedings{huoh2021encrypted,
  title={Encrypted network traffic classification using a geometric learning model},
  author={Huoh, Ting-Li and Luo, Yan and Zhang, Tong},
  booktitle={2021 IFIP/IEEE International Symposium on Integrated Network Management (IM)},
  pages={376--383},
  year={2021},
  organization={IEEE}
}
```

