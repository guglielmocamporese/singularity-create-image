# Create a Singularity Image

With this repo you can create the singularity image for your projects. Just pull the repo and run this command:

```console
# Clone the repo
git clone https://github.com/guglielmocamporese/singularity-create-image.git
cd singularity-create-image

sudo singularity build --writable ./container.sif ./container.def
```

### Useful containers

```console
# PyTorch container
sudo singularity build --writable ./torch_container.sif ./torch_container.def

# TensorFlow container
sudo singularity build --writable ./tensorflow_container.sif ./tensorflow_container.def
```

All the containers use:
- Ubuntu 20.04
- python 3.7
