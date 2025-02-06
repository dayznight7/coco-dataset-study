@conda create -n py310 python=3.10.11
@conda activate py310
@pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
@pip install jupyter notebook
@python -m ipykernel install --user --name py310 --display-name py310kn
@python==3.10.11
@OS==win11
@cuDNN==8.9.7

Folder
├─coco_eval_AP.ipynb
├─coco_detections.json
└─coco
    ├─annotations
    └─val2017

torch==2.6.0+cu118
torchaudio==2.6.0+cu118
torchvision==0.21.0+cu118
jupyter==1.1.1
notebook==7.3.2
transformers==4.45.2
datasets==3.0.2
pycocotools==2.0.8
opencv-python==4.10.0.84
scipy==1.14.1