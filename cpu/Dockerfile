FROM deepquestai/deepstack-base:root

RUN pip3 install https://download.pytorch.org/whl/cpu/torch-1.0.0-cp35-cp35m-linux_x86_64.whl
RUN pip3 install torchvision

RUN pip3 install opencv-python
RUN apt-get update && apt install -y libsm6 libxext6
RUN apt-get install -y libxrender-dev
RUN pip3 install redis