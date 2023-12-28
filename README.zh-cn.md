# ldbm-image-background-remover

基于LDBM算法的抠图工具。

*Read this in other languages: [English](README.md), [简体中文](README.zh-cn.md).*

## 样例

[![LDBM Matting](https://github.com/whitelok/ldbm-image-background-remover/blob/master/resources/ldbm.png)](https://github.com/whitelok/ldbm-image-background-remover)

- 运行 LDBMImageBackgroundRemover:

```bash
LDBMImageBackgroundRemover /path/of/image /path/of/image_tag
```

## [下载预编译版本](https://github.com/whitelok/ldbm-image-background-remover/releases)

### Version 1.0.0
 - [Mac](https://github.com/whitelok/ldbm-image-background-remover/releases/download/1.0.0/LDBMImageBackgroundRemover)

## 编译构建

 1. Build and install [OpenCV](http://opencv.org/).
 2. Build and install [Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page).
 3. Install [Cmake](https://cmake.org/).
 4. cd ${project file}
 5. mkdir build
 6. cd build
 7. cmake ..
 8. make

## 参考文献

 - Zheng Y, Kambhamettu C. Learning based digital matting[C], Computer Vision, 2009 IEEE 12th International Conference on. IEEE, 2009: 889-896.

