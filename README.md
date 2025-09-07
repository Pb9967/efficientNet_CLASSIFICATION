# efficientNet_CLASSIFICATION
Image classification of artist based on efficientNet
`model.py`	EfficientNet-B0 + MixedConv2d 
`train.py`	
`model_test.py`	

数据摆放格式
data/artist/
├── train/
│   ├── monet/
│   ├── picasso/
│   └── van_gogh/
└── val/
    ├── monet/
    ├── picasso/
    └── van_gogh/

train.py使用

bash
python model_test.py --img "your_pic.jpg" --ckpt your_model_path
