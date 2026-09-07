# Image Report - Plan

## Per-image fields(4)
1. File name
2. Height and width
3. Mean brightness (0 - 255)
4. Ratio of dark pixels - "dark" defined by the threshold

## Summary fields(3)
5. Number of images
6. Mean brightness across all images
7. Name of the darkest image

## Command-Line argument(1)
- Darkness threshold

## Edge cases(3)
1. Folder does not exist
2. Folder contains no images
3. File cannot be read / is broken / is not an image
