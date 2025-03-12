# CoalMine-LowLight-PairedDataset 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A specialized paired dataset for low-light enhancement in coal mining environments, containing **2,620 aligned image pairs** from diverse monitoring systems.

**📦 Download**：[百度网盘链接](https://pan.baidu.com/s/1FSsPeRPvrj6r2yXrd_Emhw?pwd=1234) 提取码：1234

## Dataset Composition

| Category              | Low-Light Images | Normal-Light Pairs |
|-----------------------|------------------|--------------------|
| Underground Captures  | 998              | 998                |
| Surface-Generated     | 1622              | 1622                |

**Total**: 2,620 paired samples (5,240 individual images)

## Key Features
- 🚧 **Real-World Diversity**: Captured using various industrial monitoring devices
- ⚡ **Perfect Pairing**: Pixel-aligned low/normal-light pairs
- 🏭 **Scenario Coverage**:
  - Underground: Mining faces, equipment clusters, transport tunnels
  - Surface: Controlled illumination simulations
- 🔧 **Device Robustness**: Mixed image acquisition systems for model generalization

MELOL-Dataset.zip
├── train/
│   ├── high/        
│   └── low/         
└── test/
    ├── high/        
    └── low/         
## Citation

If you find this work helpful, please consider citing our paper:

```bibtex
@article{sun2025meformer,
  title = {MEFormer: Enhancing Low-Light Images While Preserving Image Authenticity in Mining Environments},
  author = {Zhenming Sun and Zeqing Shen and Ning Chen and Shuoqi Pang and Hui Liu and Yimeng You and Haoyu Wang and Yiran Zhu},
  journal = {Remote Sensing},
  year = {2025},
  volume = {},
  number = {},
  pages = {},
  doi = {},
  publisher = {MDPI}
}
