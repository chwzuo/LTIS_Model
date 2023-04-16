# Low-texture Image Stitching

The **L**ow-**t**exture **I**mage **S**titching (**LTIS**) model produces panorama after inputting two or more images with overlapping regions, which performs well in both regular scenes and low-texture scenes.

## Preparation

Put the folder that contains a set of pictures in the `input-data` folder.

For example: `/input-data/<image_folder>/<img_1>.png` and `/input-data/<image_folder>/<img_2>.png`.

Stitching:

```
cd main
./LTIS <image_folder>
```

The results will be saved in `input-data/0_results`.

