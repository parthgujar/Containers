# Repo for hosting containers that I create 

1. TensorFlow-gpu Object Detection on Nvidia-docker with transfer learning model and dataset 
```
nvidia-docker run -it -p 6006:6006 -p 8888:8888 -d tfgpu/od:1
```

2. Tensorflow-GPU and all gym.openai.com environments along with all dependencies
```
docker run -it -p 8080:8080 -d parth121294/one:rl 
jupyter notebook --ip=0.0.0.0 --port=8080 --allow-root 
```
