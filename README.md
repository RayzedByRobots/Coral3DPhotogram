# Bash and Python scripts for running Agisoft Metashape on a remote HPC server 

Wyatt Million wmillion@usc.edu 

We have developed a workflow in order to build 3D models of Acropora cervicornis coral colonies through a remote HPC system. Aigsoft Metashape is most commonly used through a GUI window however the software's speed is severely limited by processing power of standard personal computers. In an effort to automate 3D model building, we have generated a series of scripts to input 2D photographs for multiple models in sequence. Metashape requires a license so our workflow works by submitting jobs one after another to build models on a single license. 

API manuals from Agisoft are not straightforward so we hope to provide more user-friendly scripts/workflow as well as an example to go through the protocol on your own.
