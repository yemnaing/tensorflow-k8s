# tensorflow-k8s

$ docker run -u $(id -u):$(id -g) --gpus all -it --rm --name my_tf_container -v ~/docker_ws:/notebooks -p 8888:8888 -p 6006:6006 tensorflow/tensorflow:latest-gpu-py3-jupyter
