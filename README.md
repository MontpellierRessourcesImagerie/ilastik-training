# ilastik-training
Dockerfile to build a docker image for ilastik.
Use 

run -it -v /tmp/.X11-unix:/tmp/.X11-unix -v $(pwd):/data -e DISPLAY  baecker/ilastik-training /ilastik-1.3.0-Linux/run_ilastik.sh

to run it with x-forwarding and mapping of the current folder to the folder /data in the image.

