# singularity-docker-fedora30-brave
fedora30 container to run brave (at library://tru/default/f30-brave)


Running without installation:
```
singularity run  -B /run library://tru/default/f30-brave
```
Building:
```
sudo singularity build singularity-docker-fedora30-brave.sif  Singularity
```
Download and rename:
```
singularity pull --name singularity-docker-fedora30-brave.sif library://tru/default/f30-brave
```
Running with a separate $HOME  (here ~/singularity.d/home/singularity-docker-fedora30-brave)
```
mkdir -p  ~/singularity.d/home/singularity-docker-fedora30-brave
singularity run  -B /run  -H ~/singularity.d/home/singularity-docker-fedora30-brave singularity-docker-fedora30-brave.sif
```
