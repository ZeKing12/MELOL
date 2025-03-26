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
@Article{rs17071165,
AUTHOR = {Sun, Zhenming and Shen, Zeqing and Chen, Ning and Pang, Shuoqi and Liu, Hui and You, Yimeng and Wang, Haoyu and Zhu, Yiran},
TITLE = {MEFormer: Enhancing Low-Light Images While Preserving Image Authenticity in Mining Environments},
JOURNAL = {Remote Sensing},
VOLUME = {17},
YEAR = {2025},
NUMBER = {7},
ARTICLE-NUMBER = {1165},
URL = {https://www.mdpi.com/2072-4292/17/7/1165},
ISSN = {2072-4292},
DOI = {10.3390/rs17071165}
}
