# TRYRAPIDS
RAPIDS 

SSH to Amazon AWS Nvidia Image:

Launch Nvidia Docker Image:

```bash
docker run --runtime=nvidia --rm -it -p 8889:8889 -p 8787:8787 -p 8786:8786 nvcr.io/nvidia/rapidsai/rapidsai:0.9-cuda10.0-runtime-ubuntu18.04
```

Launch Jupyter Notebook:
```bash
jupyter notebook --allow-root --ip 0.0.0.0 --port 8889
```
