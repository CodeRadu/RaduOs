# RaduOS
This will guide you step-by-step on how to build this os on your machine
## Qemu
You will have to install QEMU on your computer
## Docker
You will have to install Docker on your computer
## Building
### Docker image
Open a command prompt and run `buildimage`  
It will take a little while (~ 2 mins)
### Running container
In cmd run `startcontainer`. This will start a docker container
### Compiling OS
In the docker container shell run `sh ./build.sh`. This will compile the os and make an .iso file
When its done run `exit`, which will exit and stop the container
## Running
Just run `run` in a cmd and this will start qemu with the OS