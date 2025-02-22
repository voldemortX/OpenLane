# Data Download
We provide three download links here to access the OpenLane dataset.
* [OpenDataLab](https://opendatalab.com/datasets/330)
* [Google Drive](https://drive.google.com/drive/folders/1fTC80RHy3HXA1-qYV26JUl2ggqIiDK-Z?usp=sharing)
* [Baidu Cloud](https://pan.baidu.com/s/1-EMPHlqTkh1LMZzdSD9NvQ?pwd=f7cr)

The entire folder hierarchy is shown below.
```
├── images
|   ├── training
|   |   ├── segment-xxx
|   |   |   ├── xxx.jpg
|   |   |   └── ...
|   |   ├── segment-xxx
|   |   |   ├── xxx.jpg
|   |   |   └── ...
|   |   └── ...
|   └── validation
|       ├── segment-xxx
|       |   ├── xxx.jpg
|       |   └── ...
|       ├── segment-xxx
|       |   ├── xxx.jpg
|       |   └── ...
|       └── ...
├── cipo
|   ├── training
|   |   ├── segment-xxx
|   |   |   ├── xxx.jpg.json
|   |   |   └── ...
|   |   ├── segment-xxx
|   |   |   ├── xxx.jpg.json
|   |   |   └── ...
|   |   └── ...
|   └── validation
|       ├── segment-xxx
|       |   ├── xxx.jpg.json
|       |   └── ...
|       ├── segment-xxx
|       |   ├── xxx.jpg.json
|       |   └── ...
|       └── ...
├── lane3d_300
|   ├── training
|   |   ├── segment-xxx
|   |   |   ├── xxx.json
|   |   |   └── ...
|   |   ├── segment-xxx
|   |   |   ├── xxx.json
|   |   |   └── ...
|   |   └── ...
|   ├── validation
|   |   ├── segment-xxx
|   |   |   ├── xxx.json
|   |   |   └── ...
|   |   ├── segment-xxx
|   |   |   ├── xxx.json
|   |   |   └── ...
|   |   └── ...
|   └── test
|       ├── curve_case
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   └── ...
|       ├── extreme_weather_case
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   └── ...
|       ├── intersection_case
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   └── ...
|       ├── merge_split_case
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   └── ...
|       ├── night_case
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   └── ...
|       ├── up_down_case
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   └── ...
|       ├── curve.txt
|       ├── extreme_weather.txt
|       ├── intersection.txt
|       ├── merge_split.txt
|       ├── night.txt
|       └── up_down.txt
├── lane3d_1000
|   ├── training
|   |   ├── segment-xxx
|   |   |   ├── xxx.json
|   |   |   └── ...
|   |   ├── segment-xxx
|   |   |   ├── xxx.json
|   |   |   └── ...
|   |   └── ...
|   ├── validation
|   |   ├── segment-xxx
|   |   |   ├── xxx.json
|   |   |   └── ...
|   |   ├── segment-xxx
|   |   |   ├── xxx.json
|   |   |   └── ...
|   |   └── ...
|   └── test
|       ├── curve_case
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   └── ...
|       ├── extreme_weather_case
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   └── ...
|       ├── intersection_case
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   └── ...
|       ├── merge_split_case
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   └── ...
|       ├── night_case
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   └── ...
|       ├── up_down_case
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   ├── segment-xxx
|       |   |   ├── xxx.json
|       |   |   └── ...
|       |   └── ...
|       ├── 1000_curve.txt
|       ├── 1000_extreme_weather.txt
|       ├── 1000_intersection.txt
|       ├── 1000_merge_split.txt
|       ├── 1000_night.txt
|       └── 1000_up_down.txt
└── scene
    └── SCENE
        └── scene.json
```
* Universal Rules: We use `XXX` to represent any of `images`, `cipo`, `lane3d_300` and `lane3d_1000`. We provide train/val split under `XXX/training/` and `XXX/validation/`, and it's consistent to Waymo original train/val split. `XXX/training/segment-xxx` denotes that the following files belong to a whole segment.
* `images/`: this folder contains all the front-view raw image files from [Waymo Open Dataset](https://waymo.com/open/data/perception/). We extract them from the original `tfrecord` format. It contains 1000 segments in total, 798 segments for training and 202 for validatioin.
* `cipo/`: this folder contains all the CIPO annotation. For the detail of the ground truth json files, please refer to [CIPO Annotation](../anno_criterion/CIPO/README.md)
* `lane3d_1000/`: this folder contains all 2D/3D lane annotation. In addition to train/val split, we provide several scene cases under `lane3d_1000/test/`. Each case contains segments selected from validation set for a special theme. And we provide corresponding image name in each `lane3d_1000/test/1000_XXX.txt` For the detail of the ground truth json files, please refer to [Lane Annotation](../anno_criterion/Lane/README.md)
* `lane3d_300/`: this folder contains a tiny set from `lane3d_1000/`. We provide this set for those users whose computation resource is limited. It contains 300 sequence in total, 240 for training and 60 for validation.
* `scene`: this folder contains all scene annotation. It only has one json file. For the detail of json file, please refer to [CIPO Annotation](../anno_criterion/CIPO/README.md)
