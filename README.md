# docker-compose-volume
Reference material for https://medium.com/@zhao.li/how-to-understand-working-with-files-in-containers-using-docker-compose-6d8e68ed790b

Getting Started
---------------
1. install docker
1. install docker-compose
1. clone repository: `git clone --recursive https://github.com/zhao-lin-li/docker-compose-volume.git`
1. run `docker-compose up` to run the image

To see the results, browse to `http://localhost:8081`

To stop the container, press `CTRL-C` or issue `docker-compose down`

To make changes to `index.html` in the container, just modify `index.html` on the host.

To have your changes reflected inside the container, issue `docker-compose down && docker-compose up`
