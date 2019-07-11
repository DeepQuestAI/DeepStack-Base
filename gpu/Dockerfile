FROM deepquestai/deepstack-base:cuda

WORKDIR /TEMP_DIR
COPY . /TEMP_DIR

RUN pip3 install torch-0.4.1-cp35-cp35m-manylinux1_x86_64.whl
RUN rm torch-0.4.1-cp35-cp35m-manylinux1_x86_64.whl
RUN pip3 install torchvision
RUN pip3 install tensorflow-gpu=="1.12"
RUN pip3 install onnxruntime-gpu

RUN pip3 install opencv-python
RUN apt-get update && apt install -y libsm6 libxext6
RUN apt-get install -y libxrender-dev
RUN pip3 install redis
