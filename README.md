# Laravel/Lumen Docker Image

## Downloading Image
You can download this image for Docker from the [Abdullah Hafizh Repository](https://hub.docker.com/r/abdullahhafizh/laravel), or choose another image that better suits your needs. You can search Docker Hub (the official set of repositories) for an image with this command:

    docker search abdullahhafizh
    
Once you have found an image that you want to use, you can download it via Docker. Some layers including necessary dependencies will be downloaded too. Note that, once a layer is downloaded for a certain image, Docker will not need to download it again for another image.

For example, if you want to install the image, you can type:

    docker pull abdullahhafizh/laravel
    
You will see a list of necessary layers. For each layer, Dockers will say if it is already present, or its download progress.

To get a list of installed images:

    docker images
