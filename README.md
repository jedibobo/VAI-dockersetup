# VAI-dockersetup
Vitis-AI build gpu docker files for those who cannot passwall

## how to use
just simply replace the files in Vitis-AI/docker

## Changes from original Vitis-AI setup
- add `Wget` proxy setup in DockerfileGPU
- change gpu_conda/*.yml files to connect to `mirrors.tuna.tsinghua.edu.cn`
note that if you add more channels in `*.yml` files, it will take **much longer time** to resolve repos.
