# WIP: Simple scaling script for CycleCloud SLURM

Scaling isn't working, see [this issue](https://github.com/Azure/cyclecloud-slurm/issues/11).

Let's do it ourselves.


Setup Python 2
```
conda create -n python2 python=2
conda activate python2
```

Download and install the CLI tools
```
wget https://chet.southcentralus.cloudapp.azure.com/download/tools/cyclecloud-cli.zip
unzip cyclecloud-cli.zip
cd cyclecloud-cli-installer
./install.sh
```
