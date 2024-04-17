# SemiSA
This is a deep learning model for segmenting Scanning Acoustic Tomography images of Semiconductor Devices.


## Libraries Requirement
This project depends on the following libraries:
- Python_requires>=3.9
- Monai
- Scikit-image
- SimpleITK>=2.2.1
- Nibabel
- Tqdm
- Scipy
- Opencv-python
- Ipywidgets
- Onnx
- Onnxruntime

## Training
Download [SAM checkpoint](https://dl.fbaipublicfiles.com/segment_anything/sam_vit_b_01ec64.pth) and place it at `work_dir/SAM/`

```bash
python train.py
```

## GUI

Install `C++` and `C#`

```bash
python gui.py
```

## Result
![GUI of Ohlab SemiSA](/Data/SemiSA_Tool.png)

## Acknowledgements
- We appreciate Meta AI for publicly sharing the source code [SAM](https://github.com/facebookresearch/segment-anything) for the Segment Anything model.
- Any ideas on updating or misunderstanding, please send me an email: havuthithu96@gmail.com

