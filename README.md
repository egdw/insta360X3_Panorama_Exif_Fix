# insta360X3_Panorama_Exif_Fix

## 目的 Purpose

我想要将insta360 x3生成的全景图上传到Google Photos,但是我发现通过insta360 studio导出的全景图无法被谷歌有效的识别,因此决定实现一个批处理解决全景图无法识别问题的代码.

I want to upload the panoramic photos generated by insta360 x3 to Google Photos. However, I found that the panoramic photos exported through insta360 studio cannot be recognized effectively by Google. Therefore, I decided to create a batch processing code to solve the issue of panoramic photos not being recognized.

## 原理 Principle

利用exiftool添加有关于全景图的xmp信息即可被谷歌相册识别.

By using exiftool, we can add XMP information related to the panoramic photos, which allows Google Photos to recognize them.

## 要求 Requirements

需要在自己的本机上安装好exiftool,详情请查看官网[exiftool官网](https://exiftool.org/)

You need to install exiftool on your local machine. For more details, please refer to the official website:[exiftool offical website](https://exiftool.org/)

## 使用方法 How to use?

利用insta360 studio导出相关图片,随后将原始python文件放置于导出图片相同目录下,并执行.

```
python3 main.py
```

Export the relevant images using Insta360 Studio, then place the original Python file in the same directory as the exported images, and execute the following command:

```
python3 main.py
```

## result 

<img width="1438" alt="image" src="https://github.com/egdw/insta360X3_Panorama_Exif_Fix/assets/20622517/a09aa8ab-0d88-4499-808c-92b64f5e2ac5">
