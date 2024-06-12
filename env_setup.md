# `conda` Environment Setup Instructions

1. `conda create -n csu101 python=3.12 -y`
2. `conda activate csu`
3. `conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia -y`
4. `conda install lightning -c conda-forge -y`
5. `pip install opencv-python tqdm, ipykernel matplotlib torchmetrics`