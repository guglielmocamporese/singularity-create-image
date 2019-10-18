# Singularity Image

With this repo you can create the singularity image for your projects. Just pull the repo and run this command in the folder **singularity-create-image**:


`sudo singolarity build --writable container.sif container.def`

<hr>

List of things that you are going to install in the image will be:
- Ubuntu 18.04
- python3.7
- numpy 1.17.2
- matplotlib 3.1.1
- tensorflow-gpu 1.14
- tensorflow_probability 0.7
- opencv 4.1.1.26
