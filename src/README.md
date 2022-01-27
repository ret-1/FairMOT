### 文件结构
```
.
├── README.md
├── _init_paths.py
├── cfg
│   ├── crowdhuman.json
│   ├── data.json
│   ├── data_all.json
│   ├── data_half.json
│   ├── mot15.json
│   ├── mot16.json
│   ├── mot17.json
│   ├── mot17_half.json
│   └── mot20.json
├── data
│   ├── caltech.10k.val
│   ├── caltech.all
│   ├── caltech.train
│   ├── caltech.val
│   ├── citypersons.train
│   ├── citypersons.val
│   ├── crowdhuman.train
│   ├── crowdhuman.val
│   ├── cuhksysu.train
│   ├── cuhksysu.val
│   ├── eth.train
│   ├── mot15.train
│   ├── mot16.train
│   ├── mot17.emb
│   ├── mot17.half
│   ├── mot17.train
│   ├── mot17.val
│   ├── mot20.train
│   ├── prw.train
│   └── prw.val
├── datasets
│   ├── dataset
│   └── dataset_factory.py
├── demo.py
├── detect.py
├── detection_demo.py
├── logger.py
├── models -- 模型定义
│   ├── common.py
│   ├── data_parallel.py
│   ├── decode.py
│   ├── losses.py
│   ├── model.py
│   ├── networks
│   ├── scatter_gather.py
│   ├── utils.py
│   └── yolo.py
├── opts.py -- 解析命令行参数
├── script -- 一些生成脚本
│   ├── gen_data_path.py
│   ├── gen_labels_15.py
│   ├── gen_labels_16.py
│   ├── gen_labels_20.py
│   ├── gen_labels_crowd_det.py
│   └── gen_labels_crowd_id.py
├── test_det.py
├── test_emb.py
├── track.py -- 跟踪
├── track_half.py
├── tracker
│   ├── basetrack.py
│   ├── matching.py
│   └── multitracker.py
├── tracking_utils
│   ├── evaluation.py
│   ├── io.py
│   ├── kalman_filter.py
│   ├── log.py
│   ├── nms.py
│   ├── parse_config.py
│   ├── timer.py
│   ├── utils.py
│   └── visualization.py
├── train.py -- 训练
├── trains
│   ├── base_trainer.py
│   ├── mot.py
│   └── train_factory.py
└── utils
    ├── image.py
    ├── post_process.py
    └── utils.py
```
