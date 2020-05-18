# About

This repository is for my personal website.

The backbone codes belong to this repo: https://github.com/barryclark/jekyll-now

Some of my own modifications:

(1) Add tags<br>
(2) Add gallery<br>
(3) Scripts (some were writen by me, some were adopted from the others with some modifications): `assets/scripts`

## Script usages
Requirements: `./requirements.sh`

### Tag generators
When new tags are added, run the following script to generate tags:
```bash
python ./assets/scripts/tag_generator.py
```

### Gallery
To create gallery, after adding new image, several sizes of images needed to be created, using this script:
```bash
assets/scripts/resize_img.sh <path_to_txt_ls_of_files>
```

After that, run:
```bash
assets/scripts/gallery_generator.py -type [drawings|photography]
```

