# singularity-docker-centos7-devtoolset
devtoolset singularity container on CentOS-7

```
Running without installation:
singularity run shub://truatpasteurdotfr/singularity-docker-centos7-devtoolset
Building:
singularity build devtoolset Singularity
Download and rename:
singularity pull --name "devtoolset" shub://truatpasteurdotfr/singularity-docker-centos7-devtoolset
Running with a separate $HOME 
mkdir -p  ~/singularity.d/home/devtoolset 
singularity run -H  ~/singularity.d/home/devtoolset ./devtoolset 
```
