### Jupyter Notebook running PyTorch on GPU / cuDNN (CUDA 8.0 / cuDNN 5.1)

#### How to use

```
mkdir notebooks

nvidia-docker run -it -p 8888:8888 -d -v notebooks:/notebooks durgeshm/jupyter-pytorch-gpu

OR

nvidia-docker run -it -P -d -v notebooks:/notebooks durgeshm/jupyter-pytorch-gpu
```

Then, navigate to http://localhost:8888 on your host browser. (or, better - ssh tunnel to host server on port 8888 and navigate from your local machine).

Appropriate NVIDIA drivers and nividia-docker must be installed on the host.

