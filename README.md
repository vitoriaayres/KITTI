<div align="center">

# KITTI

**Workspace for experiments with the KITTI Vision Benchmark Suite — autonomous-driving computer vision.**

*English* · [Português](#-português)

</div>

> 🇧🇷 **Português:** repositório de trabalho para experimentos com o dataset **KITTI**, referência em visão computacional para veículos autônomos (detecção de objetos, segmentação, estimativa de profundidade e rastreamento).

## About

This repository is the starting point for experiments built on the **[KITTI Vision Benchmark Suite](http://www.cvlibs.net/datasets/kitti/)**, the standard dataset for autonomous-driving research released by the Karlsruhe Institute of Technology and Toyota Technological Institute at Chicago.

## Planned scope

- **2D/3D object detection** — cars, pedestrians, cyclists in urban scenes
- **Semantic segmentation** — pixel-level labelling of road, vegetation, buildings
- **Depth estimation** — stereo disparity and lidar-based ground truth
- **Object tracking** — multi-frame association of detected instances

## Dataset overview

| Property | Value |
|---|---|
| Images | 7,481 labelled + 7,518 unlabelled |
| Resolution | 1242 × 375 (typical) |
| Modality | colour, greyscale, lidar, GPS/IMU |
| Classes | car, van, truck, pedestrian, cyclist, tram, misc |

Datasets are downloaded from the official KITTI site and are **not** committed to this repository.

## Getting started

```bash
git clone https://github.com/vitoriaayres/KITTI.git
cd KITTI
```

> 🚧 Content in progress — notebooks, evaluation scripts and results will land here as the experiments progress.

## 🇧🇷 Português

- **O que é:** repositório de trabalho para experimentos com o dataset KITTI de visão computacional para veículos autônomos.
- **Escopo planejado:** detecção de objetos 2D/3D, segmentação semântica, estimativa de profundidade e rastreamento de objetos.
- **Sobre o dataset:** 7.481 imagens rotuladas, multimodal (cor, lidar, GPS/IMU), referência acadêmica em condução autônoma.
- **Status:** em construção — notebooks e scripts serão adicionados conforme os experimentos avançarem.

## Author

[Vitoria AYRES](https://github.com/vitoriaayres)
