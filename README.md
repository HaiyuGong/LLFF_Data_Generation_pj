# LLFF_Data_Generation_pj
The repository is adapted from `flyingshan`'s project [LLFF_Data_Generation_WIN](https://github.com/flyingshan/LLFF_Data_Generation_WIN)

Use COLMAP to generate LLFF format dataset on WIN11

## Pre-requisite:

Install [COLMAP](https://github.com/colmap/colmap/releases) (add installation path to system PATH environmental variable) and [ImageMagick](https://imagemagick.org/script/download.php#windows) on your WIN11, such as [ImageMagick-7.1.1-33-Q16-HDRI-x64-static.exe](https://imagemagick.org/archive/binaries/ImageMagick-7.1.1-33-Q16-HDRI-x64-static.exe)

## Run:
Run the following code in your terminal:
```bash
python imgs2poses.py --scenedir ./ania
```
`./ania` is the dir of your scene and the images should be placed in the dir `./ania/images`.  

## Data 
You can access the data through the link of [Baidu Pan](https://pan.baidu.com/s/1uI7YOFc8FF4aOMzqOfPG7w?pwd=oa7e). 
+ `ania_raw_zip` contains the raw image obtained by cellphone
+  `ania_llff.zip` contains the processed data by running the above command.
## Ref:
+ [LLFF](https://github.com/Fyusion/LLFF)
+ [LLFF_Data_Generation_WIN](https://github.com/flyingshan/LLFF_Data_Generation_WIN)


