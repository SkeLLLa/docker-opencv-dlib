# docker-opencv-dlib

Docker image with compiled OpenCV and Dlib

Based on [opencv image](https://hub.docker.com/r/m03geek/opencv/)

# Dlib

Dlib is built from source. Latest git tag corresponds Dlib version.

## Compile options

```
-D CMAKE_BUILD_TYPE=RELEASE
-D CMAKE_INSTALL_PREFIX=$LIB_PREFIX
-D DLIB_NO_GUI_SUPPORT=OFF
-D DLIB_USE_BLAS=ON
-D DLIB_GIF_SUPPORT=ON
-D DLIB_PNG_SUPPORT=ON
-D DLIB_JPEG_SUPPORT=ON
-D DLIB_USE_CUDA=OFF"
```

## Image support

* png
* jpeg
* gif

## FFmpeg support

FFmpeg support is available in different image:
* [DockerHub](https://hub.docker.com/r/m03geek/ffmpeg-opencv-dlib/)
* [Github](https://github.com/SkeLLLa/docker-ffmpeg-opencv-dlib)
