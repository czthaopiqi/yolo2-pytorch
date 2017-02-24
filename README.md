# YOLOv2 in PyTorch
This is a [PyTorch](https://github.com/pytorch/pytorch)
implementation of YOLOv2.
This project is mainly based on [darkflow](https://github.com/thtrieu/darkflow)
and [darknet](https://github.com/pjreddie/darknet).

For details about YOLO and YOLOv2 please refer to the [paper](https://arxiv.org/abs/1612.08242):
YOLO9000: Better, Faster, Stronger by Joseph Redmon and Ali Farhadi.


### Installation and demo
1. Clone the this repository
    ```bash
    git clone git@github.com:longcw/yolo2-pytorch.git
    ```

2. Build reorg layer
    ```bash
    cd yolo2-pytorch
    ./make.sh
    ```
3. Download the trained model [yolo-voc.weights.h5](https://drive.google.com/open?id=0B4pXCfnYmG1WUUdtRHNnLWdaMEU) 
and set the model path in `demo.py`
3. Run demo `python demo.py`