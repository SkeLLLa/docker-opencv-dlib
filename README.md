# docker-opencv-dlib

Docker image with compiled OpenCV and Dlib

[![](https://images.microbadger.com/badges/version/m03geek/opencv-dlib:alpine.svg)](https://microbadger.com/images/m03geek/opencv-dlib:alpine "version")[![](https://images.microbadger.com/badges/image/m03geek/opencv-dlib:alpine.svg)](https://microbadger.com/images/m03geek/opencv-dlib:alpine "layers")

[![](https://images.microbadger.com/badges/version/m03geek/opencv-dlib:stretch.svg)](https://microbadger.com/images/m03geek/opencv-dlib:stretch "version")[![](https://images.microbadger.com/badges/image/m03geek/opencv-dlib:stretch.svg)](https://microbadger.com/images/m03geek/opencv-dlib:stretch "layers")

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

# Other images:

## Without FFmpeg

| OpenCV | OpenCV+Dlib | OpenCV+Dlib+Node.js | OpenCV+Node.js |
|-|-|-|
| [Docker](https://hub.docker.com/r/m03geek/opencv/) | [Docker](https://hub.docker.com/r/m03geek/opencv-dlib/) | [Docker](https://hub.docker.com/r/m03geek/opencv-dlib-node/) | [Docker](https://hub.docker.com/r/m03geek/opencv-node/) |
| [Github](https://github.com/SkeLLLa/docker-opencv) | [Github](https://github.com/SkeLLLa/docker-opencv-dlib) | [Github](https://github.com/SkeLLLa/docker-opencv-dlib-node) | [Github](https://github.com/SkeLLLa/docker-opencv-node) |

## With FFmpeg

| OpenCV | OpenCV+Dlib | OpenCV+Dlib+Node.js | OpenCV+Node.js |
|-|-|-|
| [Docker](https://hub.docker.com/r/m03geek/ffmpeg-opencv/) | [Docker](https://hub.docker.com/r/m03geek/ffmpeg-opencv-dlib/) | [Docker](https://hub.docker.com/r/m03geek/ffmpeg-opencv-dlib-node/) | [Docker](https://hub.docker.com/r/m03geek/ffmpeg-opencv-dlib-node/) |
| [Github](https://github.com/SkeLLLa/docker-ffmpeg-opencv) | [Github](https://github.com/SkeLLLa/docker-ffmpeg-opencv) | [Github](https://github.com/SkeLLLa/docker-ffmpeg-opencv-dlib-node) | [Github](https://github.com/SkeLLLa/docker-ffmpeg-opencv-node) |